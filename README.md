# Tìm hiểu về AdGuard DNS
## DNS là gì?
DNS là viết tắt của **Domain Name System** hay *hệ thống phân giải tên miền.* Có thể hiểu đơn giản DNS là một “quyển địa chỉ” của Internet, trình duyệt và ứng dụng sẽ sử dụng để dịch tên miền sang một địa chỉ IP máy có thể hiểu được.
## AdGuard DNS là gì?
**AdGuard DNS** là một hệ thống phân giải DNS miễn phí, hướng đến sự riêng tư của người dùng, ngăn chặn theo dõi, quảng cáo và đặc biệt là phishing (lừa đảo), bạn có thể sử dụng AdGuard DNS để thay thế cho DNS mình đang sử dụng.
## AdGuard DNS hoạt động như thế nào?
Khi sử dụng AdGuard DNS để chặn quảng cáo, trình duyệt và ứng dụng của bạn sẽ gửi yêu cầu thông qua máy chủ của AdGuard, nếu chúng gửi yêu cầu đến các server quảng cáo, AdGuard sẽ trả lời bằng một phản hồi trống.
<br><br>
Để làm được điều này, AdGuard có một danh sách dài các tên miền chuyên phục vụ cho quảng cáo, theo dõi hay gian lận và được cập nhật khá thường xuyên. Để giúp người dùng có lựa chọn tốt hơn, AdGuard cung cấp 2 chế độ AdGuard DNS bao gồm:
- **AdGuard DNS thông thường:** lọc quảng cáo, web độc hại, lừa đảo và các trang theo dõi.
- **AdGuard DNS gia đình:** giống như AdGuard DNS thông thường nhưng còn lọc thêm website nội dung 18+.

![](https://user-images.githubusercontent.com/87995853/195999992-7b668f79-f92d-4da5-92ba-79ee4fa2703f.png)

# Ưu điểm và nhược điểm của AdGuard DNS
## Ưu điểm của AdGuard DNS
- Bạn sẽ không cần phải cài đặt bất kỳ phần mềm hay ứng dụng nào vào thiết bị của mình
- AdGuard DNS hoàn toàn miễn phí, mã nguồn mở cho các cá nhân sử dụng.
- Hiện tại, AdGuard DNS hỗ trợ rất nhiều tiêu chuẩn bảo mật và mã hóa DNS hiện đại như: DNSCrypt, DNS-over-HTTPS và DNS-over-TLS.
- 2 chế độ thông thường và gia đình sẽ giúp phụ huynh quản lý mọi thứ tốt hơn :<
- Bạn có thể sử dụng AdGuard DNS trên hầu hết các thiết bị từ máy tính, điện thoại cho đến máy chơi game.
- Theo AdGuard, họ sẽ không ghi lại dữ liệu cá nhân hoặc hoạt động của bạn.
- Giúp website tải nhanh hơn vì quảng cáo thường là thành phần tải chậm và nặng nhất triển một website.
## Nhược điểm của AdGuard DNS
- Không thể chặn tất cả các trang web quảng cáo
- Có rất nhiều website yêu cầu tắt trình chặn quảng cáo để tiếp tục truy cập
- Để lại rất nhiều khoảng trống trên website khiến giao diện website đôi khi - khá kỳ quặc (nhưng không ảnh hưởng cho lắm).
- Bạn chỉ có thể chọn 1 trong 2 VPN hoặc DNS nếu sử dụng phiên bản miễn phí khi
- kết nối. Nếu muốn sử dụng cả 2, bạn sẽ phải mua AdGuard VPN.

# Cách cài đặt AdGuard DNS trên Android và Windows 10
## Cách cài đặt AdGuard DNS trên Android
**Bước 1**: truy cập vào **Cài đăt** => và tìm đến **Kết nối & chia sẻ** hoặc **Wi-Fi & Internet** tùy theo từng thiết bị.(tip: bạn tìm kiếm DNS là ra :v)
<br>
**Bước 2**: bạn tiếp tục nhấn vào **DNS cái nhân** DNS để mở chỗ thay đổi DNS.
<br>

![](https://raw.githubusercontent.com/dieenx/AdGuard-DNS/main/png/PicsArt.png)

<br>

**Bước 3**: bạn chọn vào **Hostname nhà cung cấp DNS cái nhân** và thêm 1 trong 3 đường link sau để sử dụng AdGuard DNS:
<br>

- **dns.adguard.com**: đây là server AdGuard DNS thông thường
```
dns.adguard.com
```
- **dns-unfiltered.adguard.com**: Nếu bạn không muốn AdGuard DNS chặn gì và chỉ thay đổi DNS.
```
dns-unfiltered.adguard.com
```
- **dns-family.adguard.com**: đây là AdGuard DNS gia đình giúp chặn nội dung 18+ và những nội dung như trong AdGuard DNS thông thường.
```
dns-family.adguard.com
```

**Bước 4**: bạn nhấn vào **Lưu** để lưu lại và trải nghiệm cuộc sống không còn hàng tá quảng cáo.
# Cách cài đặt AdGuard DNS trên Windows 10
**Bước 1**: bạn gõ **Control Panel** trong menu **Start** để mở **Control Panel**.
<br>
**Bước 2**: bạn nhấn vào **View network status and tasks**

![](https://raw.githubusercontent.com/dieenx/AdGuard-DNS/main/png/windows-dns-1.png)
<br>
**Bước 3**: bạn tiếp tục chọn vào tab **Connections**:

![](https://raw.githubusercontent.com/dieenx/AdGuard-DNS/main/png/windows-dns-2.png)
**Bước 4**: bạn ấn vào  **Properties** 

![](https://raw.githubusercontent.com/dieenx/AdGuard-DNS/main/png/windows-dns-3.png)
<br>
**Bước 5**: bạn tiếp tục tìm đến **Internet Protocol Version 4** trong danh sách và nhấn vào **Properties**
- bạn chọn 1 trong 3 cặp địa chỉ dưới đây và điền vào 2 trường: **Preferred DNS** server và **Alternate DNS server** nhé!

**AdGuard DNS thông thường**
```
94.140.14.14
```

```
94.140.15.15
```

**AdGuard DNS nhưng không lọc gì cả**
```
94.140.14.140
```

```
94.140.14.141
```

**AdGuard DNS gia đình**
```
94.140.14.15
```

```
94.140.15.16
```

![](https://raw.githubusercontent.com/dieenx/AdGuard-DNS/main/png/windows-dns-4.png)

**Bước 6**: bạn tiếp tục tìm đến **Internet Protocol Version 6** trong danh sách và nhấn vào **Properties**.
- bạn tiếp tục chọn vào **Use the following DNS server addresses** và chọn 1 trong 3 cặp địa chỉ dưới đây để nhập vào nhé!

**AdGuard DNS thông thường**
```
2a10:50c0::ad1:ff
```

```
2a10:50c0::ad2:ff
```

**AdGuard DNS nhưng không lọc gì cả**
```
2a10:50c0::1:ff
```

```
2a10:50c0::2:ff
```

**AdGuard DNS gia đình**
```
2a10:50c0::bad1:ff
```

```
2a10:50c0::bad2:ff
```


![](https://raw.githubusercontent.com/dieenx/AdGuard-DNS/main/png/windows-dns-5.png)


**Bước 7**: bạn nhấn **OK** để lưu lại và **Close** để đóng toàn bộ mọi thứ. Lúc này, bạn có thể tùy chọn **khởi động lại thiết bị** hoặc tiếp tục sử dụng như thông thường với ít quảng cáo nhất có thể.
<br>
Nếu bạn muốn tham khảo cách thực hiện trên iOS và macOS, bài viết hướng dẫn của [AdGuard DNS](https://adguard-dns.io/en/public-dns.html) sẽ giúp bạn nhiều đấy!
