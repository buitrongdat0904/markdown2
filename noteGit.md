# Lệnh git cơ bản đẻ upload một file lên GitHub.
  ### 1. Nhập tên/gmai trong git bằng lệnh: *git config --global user.name "your_name"\ git config --global user.email "your_email"*.
  > Trong đó *--global* được sử dụng để áp dụng cho tất cả các projects. Nếu bạn ko sử dụng --global thì settings sẽ chỉ dùng cho riêng project đó.
  
  ### 2. Lênh sao chép lại kho dữ liệu đã cso sẵn trên git từ trước: *git clone https://github.com/user/.............*
        > Câu lệnh trên sẽ tạo một thư mục mới có tên giống trên của repo.
  
  ### 3.Lệnh cập nhật *git add .*  ----------> *git commit -m "Nội dung"*  
  
        Sau khi thay đổi dữ liệu  source code: thêm mới, sửa, xoá files thì cần phải cập nhật lên Staging Area.
        Để cập nhật hết các files lên: $ git add .      
        Sau lệnh add, bạn cần sử dụng câu lệnh Commit để đây thông tin thay đổi lên Local Respository: git commit -m "Message"
  
  ### 4. Tạo 1 tag cho các file muốn tải lên vd tag là: "bandautien"
         câu lệnh: *git tag bandautien*         
           
 ### 5. tạo không gian để đấy file/folder lên git: *git push origin master*
 
 ### 6. Đẩy file/folder có tag vừa tạo nên : *git push origin bandautien*
         
# Cách khác
### 1. Nhập tên/gmai trong git bằng lệnh: *git config --global user.name "your_name"\ git config --global user.email "your_email"*.
  > Trong đó *--global* được sử dụng để áp dụng cho tất cả các projects. Nếu bạn ko sử dụng --global thì settings sẽ chỉ dùng cho riêng project đó.
  
  ### 2. Lênh sao chép lại kho dữ liệu đã cso sẵn trên git từ trước: *git clone https://github.com/user/.............*
        > Câu lệnh trên sẽ tạo một thư mục mới có tên giống trên của repo.
  
  ### 3.Lệnh cập nhật *git add .*  ----------> *git commit -m "first commit"*  
  
  ### 4. Git push.
  
  
  
  
  
