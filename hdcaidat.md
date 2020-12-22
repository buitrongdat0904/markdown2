
# Hướng Dẫn Cài Đặt Linux Centos 7 trên Vmware.
**Centros** là một hệ điều hành miễn phí được xây dựng và phát triển dựa trên hệ điều hành mã nguồn mở Linux. Centos là chữ viết tắt của “Community Enterprise Operating System”. CentOS ra mắt vào tháng 5/2004 và được phát triển dựa trên bản phân phối của Red Hat Enterprise Linux (RHEL).

## Chuẩn bị. 
+ tải VMware workstation Pro 15.5 [link tải](https://www.vmware.com/products/workstation-pro/workstation-pro-evaluation.html)

+ Souce ios centos 7 [link tải]( www.centos.org/download/)

+ Cấu hình tối thiểu : Ổ cứng : 40 GB , RAM : 4G

+ Cấu hình khuyến cáo : Ổ cứng : 100GB , RAM : 8GB đối với 64bit.

## Cài đặt VMware Wokstation

1. Mở file setup vmware vừa tải về Click chọn Next.
2. Đánh dấu check vào ô “I accept the terms in the License Agreement”, sau đó tiếp tục bấm Next.
3. Bước này chọn nơi mà phần mềm được lưu trữ trên máy tính của bạn, nếu không muốn thay đổi thì ta để mặc định, rồi chọn Next.
4. Tiếp tục chọn Next.
5. Đánh dấu check vào ô “Desktop” để phần mềm tạo một icon ngoài Desktop giúp bạn truy cập chương trình nhanh hơn, sau đó chọn Next.
6. Bấm chọn Install để bắt đầu tiến trình cài đặt phần mềm vào máy tính.

Sau khi cài đặt xong, click chọn Finish để hoàn tất việc cài đặt và bạn đã có thể sử dụng phần mềm.

## Cài Đặt centos 7
  **Sau khi cài đặt VMware xong chúng ta tiến hành cài đặt centos 7 như sau:**

1. Khởi động máy ảo VMware > File > New Virtual Machine.
2. Chọn Custom > Next.
3. Check vào ô I will install the operating system later. > Next.
4. Chọn Linux > Version: Centos 7 64-bit (ở đây, máy của mình là 64bit nên mình sẽ chọn là centos 7 64-bit).
5. Đặt tên và chọn nơi lưu file (đây là file đĩa ảo, file này khá nặng nên lưu ở ổ đĩa nào còn trống nhiều dung lượng để tránh gặp lỗi khi cài đặt).
6. Chọn tốc độ xử lý của máy ảo.
7. Chọn RAM,  nếu ram bạn nhiều thì có thể để lên cao hơn nữa.
8. Thiết lập card mạng cho máy ảo ( bạn có thể chọn card nat hoặc bried)
9. Thiết lập chế độ nhập xuất
10. Tiếp click Next
11. Tạo một ổ đĩa ảo mới. Chọn Create a new virtual disk > Next
12. Chọn dung lượng cho ổ đĩa đó, mình để mặc định là 40GB. NHỚ CHỌN Store virtual disk as a single file
13. Chọn đường dẫn lưu file ổ đĩa ảo, sau này có thể copy và chuyển qua máy tính khác mã vẫn dùng được máy ảo.
14. Chọn Customize Hardware để kiếm tra lại các thiếp lập.
15. New CD/DVD  (IDE) > Use ISO image file và chọn đến đường dẫn file ISO centos 7 đã tải về ở trên. Sau đó ấn Close.
16. Chọn Finish
17. Khởi động centos bằng Power on this virtual machine
18. Chọn Install centos 7
19. Thiết lập ngôn ngữ > Continue (english khuyến cáo).
20. Thiết lập ngày, giờ. DATE & TIME > Done (set giờ việt nam nhé, cứ trỏ chuột vào bản đồ việt nam)
21. Ở mục SOFTWATE SELECTION, chọn giao diện đồ hoạ (GUI) để dễ dàng thao tác:
      Server with GUI > KDE > Done
22. Mục INSTALLATION DESTINATION, chọn ổ đĩa ảo 40GB mình đã tạo lúc nãy > Done
23. Mục NETWORK & HOST NAME, chọn ON > Done
24. Chọn Begin Installation
25. Thiết lập tài khoản ROOT, tài khoản này rất quan trọng nên cần phải ghi nhớ mật khẩu
26. Chờ máy tự động cài đặt, bạn chờ khoảng 3 đến 5 phút tuỳ vào cấu hình của máy tính. Click Reboot
27. Tick chọn I accept the license agreement
28. Tạo tài khoản mới để đăng nhập vào hệ thống.
29. Set mật khẩu cho tài khoản của bạn vừa tạo lúc nãy. LƯU Ý 2 MẬT KHẨU ROOT VÀ USER KHÁC NHAU
30. Giờ ta đã có thể chạy được Centos trên máy ảo VMware.

 

Chúc các bạn cài đặt thành công, ngoài ra để có những trải kiểm tốt hơn trên máy ảo VMware khi cài đặt centos 7 các bạn có thể năng cấp ram của mình hoặc nâng cấp ổ cứng lên. 
 
