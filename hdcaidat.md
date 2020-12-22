
# Hướng Dẫn Cài Đặt Linux Centos 7 trên Vmware.
**Centros** là một hệ điều hành miễn phí được xây dựng và phát triển dựa trên hệ điều hành mã nguồn mở Linux. Centos là chữ viết tắt của “Community Enterprise Operating System”. CentOS ra mắt vào tháng 5/2004 và được phát triển dựa trên bản phân phối của Red Hat Enterprise Linux (RHEL).

## Chuẩn bị. 
+ tải VMware workstation Pro 15.5 [link tải](https://www.vmware.com/products/workstation-pro/workstation-pro-evaluation.html)

+ Souce ios centos 7 [link tải]( www.centos.org/download/)

+ Cấu hình tối thiểu : Ổ cứng : 40 GB , RAM : 4G

+ Cấu hình khuyến cáo : Ổ cứng : 100GB , RAM : 8GB đối với 64bit.

## Cài đặt VMware Wokstation

1. Mở file setup vmware vừa tải về Click chọn Next.

![setup](https://tungphatcomputer.com/images/upload/images/buoc-1-cai-dat-vmware.jpg)


2. Đánh dấu check vào ô “I accept the terms in the License Agreement”, sau đó tiếp tục bấm Next.

![setup](https://tungphatcomputer.com/images/upload/images/buoc-2-cai-dat-vmware.jpg)


3. Bước này chọn nơi mà phần mềm được lưu trữ trên máy tính của bạn, nếu không muốn thay đổi thì ta để mặc định, rồi chọn Next.

![setup](https://tungphatcomputer.com/images/upload/images/buoc-3-cai-dat-vmware.jpg)


4. Tiếp tục chọn Next.

![setup](https://tungphatcomputer.com/images/upload/images/buoc-4-cai-dat-vmware.jpg)


5. Đánh dấu check vào ô “Desktop” để phần mềm tạo một icon ngoài Desktop giúp bạn truy cập chương trình nhanh hơn, sau đó chọn Next.

![setup](https://tungphatcomputer.com/images/upload/images/buoc-5-cai-dat-vmware.jpg)


6. Bấm chọn Install để bắt đầu tiến trình cài đặt phần mềm vào máy tính.

![setup](https://tungphatcomputer.com/images/upload/images/buoc-6-cai-dat-vmware.jpg)


Sau khi cài đặt xong, click chọn Finish để hoàn tất việc cài đặt và bạn đã có thể sử dụng phần mềm.

## Cài Đặt centos 7
  **Sau khi cài đặt VMware xong chúng ta tiến hành cài đặt centos 7 như sau:**

1. Khởi động máy ảo VMware > File > New Virtual Machine.

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-1-cai-dat-centos.jpg)


2. Chọn Custom > Next.

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-2-cai-dat-centos.jpg)


3. Check vào ô I will install the operating system later. > Next.

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-3-cai-dat-centos.jpg)


4. Chọn Linux > Version: Centos 7 64-bit (ở đây, máy của mình là 64bit nên mình sẽ chọn là centos 7 64-bit).

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-4-cai-dat-centos.jpg)


5. Đặt tên và chọn nơi lưu file (đây là file đĩa ảo, file này khá nặng nên lưu ở ổ đĩa nào còn trống nhiều dung lượng để tránh gặp lỗi khi cài đặt).

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-5-cai-dat-centos.jpg)


6. Chọn tốc độ xử lý của máy ảo.

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-6-cai-dat-centos.jpg)


7. Chọn RAM,  nếu ram bạn nhiều thì có thể để lên cao hơn nữa.

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-7-cai-dat-centos.jpg)


8. Thiết lập card mạng cho máy ảo ( bạn có thể chọn card nat hoặc bried).

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-8-cai-dat-centos.jpg)


9. Thiết lập chế độ nhập xuất.

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-9-cai-dat-centos.jpg)


10. Tiếp click Next.

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-10-cai-dat-centos.jpg)


11. Tạo một ổ đĩa ảo mới. Chọn Create a new virtual disk > Next. 

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-11-cai-dat-centos.jpg)


12. Chọn dung lượng cho ổ đĩa đó, mình để mặc định là 40GB. NHỚ CHỌN Store virtual disk as a single file. 

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-12-cai-dat-centos.jpg)


13. Chọn đường dẫn lưu file ổ đĩa ảo, sau này có thể copy và chuyển qua máy tính khác mã vẫn dùng được máy ảo.

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-13-cai-dat-centos.jpg)


14. Chọn Customize Hardware để kiếm tra lại các thiếp lập.

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-14-cai-dat-centos.jpg)


15. New CD/DVD  (IDE) > Use ISO image file và chọn đến đường dẫn file ISO centos 7 đã tải về ở trên. Sau đó ấn Close.

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-15-cai-dat-centos.jpg)


16. Chọn Finish.

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-16-cai-dat-centos.jpg)


17. Khởi động centos bằng Power on this virtual machine.

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-17-cai-dat-centos.jpg)


18. Chọn Install centos 7. 

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-18-cai-dat-centos.jpg)


19. Thiết lập ngôn ngữ > Continue (english khuyến cáo).

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-19-cai-dat-centos.jpg)


20. Thiết lập ngày, giờ. DATE & TIME > Done (set giờ việt nam nhé, cứ trỏ chuột vào bản đồ việt nam). 

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-20-cai-dat-centos.jpg)


21. Ở mục SOFTWATE SELECTION, chọn giao diện đồ hoạ (GUI) để dễ dàng thao tác:
      Server with GUI > KDE > Done. 
      
      ![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-21-cai-dat-centos.jpg)
      
      
22. Mục INSTALLATION DESTINATION, chọn ổ đĩa ảo 40GB mình đã tạo lúc nãy > Done. 

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-22-cai-dat-centos.jpg)


23. Mục NETWORK & HOST NAME, chọn ON > Done. 

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-23-cai-dat-centos.jpg)


24. Chọn Begin Installation. 

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-24-cai-dat-centos.jpg)


25. Thiết lập tài khoản ROOT, tài khoản này rất quan trọng nên cần phải ghi nhớ mật khẩu.

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-25-cai-dat-centos.jpg)


26. Chờ máy tự động cài đặt, bạn chờ khoảng 3 đến 5 phút tuỳ vào cấu hình của máy tính. Click Reboot

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-26-cai-dat-centos.jpg)

27. Tick chọn I accept the license agreement. 

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-27-cai-dat-centos.jpg)


28. Tạo tài khoản mới để đăng nhập vào hệ thống.

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-28-cai-dat-centos.jpg)


29. Set mật khẩu cho tài khoản của bạn vừa tạo lúc nãy. LƯU Ý 2 MẬT KHẨU ROOT VÀ USER KHÁC NHAU.

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-29-cai-dat-centos.jpg)


30. Giờ ta đã có thể chạy được Centos trên máy ảo VMware.

![Centos7](https://tungphatcomputer.com/images/upload/images/buoc-30-cai-dat-centos.jpg)


## Cài Đặt Ubuntu 16

1. Bạn nhấn vào nút Create a New Virtual Machine.
2. Chọn dạng cài đặt là Typical => sau đó nhấn chọn Next để tiếp tục.
3. Tích chọn Installer disc image file (iso) => nhấn vào Browse..... để chọn đường dẫn trỏ tới file ISO của bộ cài Ubuntu => và Next.
4. Đặt Tên và Password (lưu ý không viết hoa chữ cái đầu tiên cho user name nhé). Sau đó nhấn Next.
    Bạn có thể đặt lại tên trong mục Virtual machine name: , hoặc có thể giữ nguyên theo mặc định => chọn Next.
5. Chọn dung lượng ổ cứng cho máy ảo như hình, theo mình bạn nên để trong khoản 20 – 50 GB tùy vào dung lượng ổ cứng và nhu cầu sử dụng của bạn.
6. Bạn có thể chọn Customize Hardware để thay đổi tùy chọn và có nhiều tùy chọn hơn.
7. Các tùy chọn có thể thay đổi như hình dưới. Nếu như máy tính của bạn có dung lượng RAM lớn, thì nên để RAM nhiều nhiều một chút để máy tính ảo chạy mượt hơn.
    Sau đó nhấn Close và Finish.
8. Giao diện cài xong như hình bên dưới => chọn Power on the virtual machine để khởi động và boot vào bộ cài Ubuntu.

Quá trình boot và bung file Ubuntu ra máy ảo đang diễn ra. Bạn đợi cho quá trình này kết thúc thôi

**Vậy là thành công rồi !**


 

Chúc các bạn cài đặt thành công, ngoài ra để có những trải kiểm tốt hơn trên máy ảo VMware khi cài đặt centos 7 các bạn có thể năng cấp ram của mình hoặc nâng cấp ổ cứng lên. 
 
