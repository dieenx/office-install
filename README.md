- [OfficeSetup.exe](https://c2rsetup.officeapps.live.com/c2r/download.aspx?productReleaseID=O365ProPlusRetail&platform=Def&language=en-us&TaxRegion=pr&correlationId=a98f2420-8b66-4259-ba9e-90eeaeb8088a&token=0009fccd-aea5-45c4-ba67-5fc257a73f11&version=O16GA&source=O15OLSO365&Br=2)

- [Download Office Customization Tools](https://www.microsoft.com/en-us/download/details.aspx?id=49117)

- [Download Office Deployment Tool](https://config.office.com/deploymentsettings)
# office-install
## Cài qua Deployment Tool
Hướng dẫn sơ bộ
- bước 1: Tạo file cấu hình và xuất file sẽ được file configuration.xml ở [officedeploymenttool_17531-20046.exe](https://www.microsoft.com/en-us/download/details.aspx?id=49117)
  ![Annotation](https://github.com/user-attachments/assets/b4604042-103b-47a1-8151-d0d91b3d9fc8)
>giải nén ra ta được file này
  ![Annotation](https://github.com/user-attachments/assets/abad4a34-cd70-4472-9095-944179514036)

- bước 2: Tạo 1 folder ở ổ c: và copy configuration.xml & OfficeSetup.exe vào folder
  ![Annotation](https://github.com/user-attachments/assets/b9496cd0-648f-4cb4-b912-415fd8dee0ec)
  và cho 2 file kia lên rồi
  ![Annotation](https://github.com/user-attachments/assets/2b3c69fc-d36c-4401-84d6-cfeaaa1add9e)
  
- bước 3: mở CMD lên với quyền admin (vd tao để ổ C và đặt tên là office)
  ```
  cd c:\office
  ```
  Setup.exe /configure configuration.xml
  ```
  cd c:\office
  ```
  ![Untitled](https://github.com/user-attachments/assets/dfe69ebe-4522-4df6-b017-4d2f27d89d08)
  ![Untitled](https://github.com/user-attachments/assets/1899edac-46fc-45cf-b01b-096926e7cb05)
  ![Untitled](https://github.com/user-attachments/assets/0e9b7b70-e43a-4f29-be9e-b4c7d1ae0716)


## Còn key thì dùng [MAS](https://github.com/massgravel/Microsoft-Activation-Scripts)
