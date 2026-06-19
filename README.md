[![MAS](https://img.shields.io/badge/MAS-MicrosoftActivationScripts-blue)](https://github.com/massgravel/Microsoft-Activation-Scripts)

# Office Install

Cài đặt Microsoft Office bằng **Office Deployment Tool (ODT)** và file cấu hình XML.

## Yêu cầu

* Windows 10 hoặc Windows 11
* Quyền Administrator
* Kết nối Internet ổn định

## Công cụ

* **Office Deployment Tool (ODT):** https://www.microsoft.com/download/details.aspx?id=49117
* **Office Customization Tool (OCT):** https://config.office.com/deploymentsettings
* [OfficeSetup.exe](https://c2rsetup.officeapps.live.com/c2r/download.aspx?productReleaseID=O365ProPlusRetail&platform=Def&language=en-us&TaxRegion=pr&correlationId=a98f2420-8b66-4259-ba9e-90eeaeb8088a&token=0009fccd-aea5-45c4-ba67-5fc257a73f11&version=O16GA&source=O15OLSO365&Br=2)
> ví dụ: seting English (United States) và chỉ cài Word, PowerPoint, Excel

`Configuration.xml`
```xml
<Configuration ID="2ec7c48a-fe53-4c9a-ab07-bd9f63ff1433">
  <Add OfficeClientEdition="64" Channel="Current">
    <Product ID="O365ProPlusRetail">
      <Language ID="en-us" />
      <ExcludeApp ID="Access" />
      <ExcludeApp ID="Groove" />
      <ExcludeApp ID="Lync" />
      <ExcludeApp ID="OneDrive" />
      <ExcludeApp ID="OneNote" />
      <ExcludeApp ID="Outlook" />
      <ExcludeApp ID="Publisher" />
    </Product>
  </Add>
  <Updates Enabled="TRUE" />
  <RemoveMSI />
</Configuration>
```

## Hướng dẫn

### Bước 1: Tải Office Deployment Tool

1. Truy cập liên kết tải ODT.
2. Tải xuống và chạy tệp cài đặt.
3. Chọn thư mục giải nén, ví dụ:

```text
C:\Office
```

Sau khi giải nén, thư mục sẽ chứa tệp:

```text
setup.exe
```

---

### Bước 2: Tạo file cấu hình

1. Truy cập Office Customization Tool.
2. Chọn phiên bản Office, ngôn ngữ và các ứng dụng cần cài đặt.
3. Chọn **Export** để tải file cấu hình.
4. Lưu file với tên:

```text
configuration.xml
```

5. Sao chép file vào thư mục `C:\Office`.

Cấu trúc thư mục:

```text
C:\Office
├── setup.exe
└── configuration.xml
```

---

### Bước 3: Cài đặt Office

1. Mở **Command Prompt** với quyền Administrator.
2. Chạy các lệnh sau:

```cmd
cd C:\Office
setup.exe /configure configuration.xml
```

Office sẽ tự động tải xuống và cài đặt theo cấu hình đã chọn.

> Thời gian cài đặt phụ thuộc vào tốc độ mạng và cấu hình máy tính.

---

### Tùy chọn: Tải bộ cài trước

Nếu muốn cài đặt ngoại tuyến hoặc sử dụng cho nhiều máy tính, chạy lệnh:

```cmd
setup.exe /download configuration.xml
```

Sau khi tải xong, cài đặt bằng lệnh:

```cmd
setup.exe /configure configuration.xml
```

## Lưu ý

* Nên gỡ bỏ các phiên bản Office cũ trước khi cài đặt.
* Đảm bảo không đổi tên tệp `setup.exe` và `configuration.xml`.
* Nếu quá trình cài đặt không bắt đầu, hãy kiểm tra lại nội dung file cấu hình và kết nối Internet.

## Tài liệu tham khảo
1. Office Deployment Tool: https://learn.microsoft.com/deployoffice/overview-office-deployment-tool
2. Office Customization Tool: https://config.office.com/
3. Microsoft 365: https://www.microsoft.com/microsoft-365
