# Một số câu lệnh trong Git
  ### Commit: git commit -m "nd commit" : lưu trữ những tahy đổi mà bạn thực hiện
  ### add: git add . : thêm toàn bộ file
  ###    : git add <file name> :thêm 1 file
  
  ### Branch:  Tạo mới một Branch:** git branch <name_branch> 
  **Khiểm tra có bao nhiêu Branch: git branch **
    > khi này thì nếu có dấu * xuất hiện trước tên branch nào thì con trỏ đang ở nhánh đó
  ### Checkout : 1. Chuyển đổi từ Branch này xang Branch khác: git checkout <name_branch> hoặc git switch <name_branch>  
                 2. Xoá 1 branch nào đó:** gỉ checkout -d <name_branch>
   
  


# Lệnh git cơ bản đẻ upload một file lên GitHub.



### 1. Nhập tên/gmai trong git bằng lệnh: *git config --global user.name "your_name"\ git config --global user.email "your_email"*.
  > Trong đó *--global* được sử dụng để áp dụng cho tất cả các projects. Nếu bạn ko sử dụng --global thì settings sẽ chỉ dùng cho riêng project đó.
  
  ### 2. Lênh sao chép lại kho dữ liệu đã cso sẵn trên git từ trước: *git clone https://github.com/user/.............*
        > Câu lệnh trên sẽ tạo một thư mục mới có tên giống trên của repo.
  
  ### 3.Lệnh cập nhật *git add .*  ----------> *git commit -m "first commit"*  
        Sau khi thay đổi dữ liệu  source code: thêm mới, sửa, xoá files thì cần phải cập nhật lên Staging Area.
        Để cập nhật hết các files lên: $ git add .      
        Sau lệnh add, bạn cần sử dụng câu lệnh Commit để đây thông tin thay đổi lên Local Respository: git commit -m "Message"
  
  ### 4. Git push.
  
  # Branch 
  ## 1. Branch là gì: Branch là nhánh mà ở đó chúng ta sẽ lưu giữ các phiên bản cụ thể của project chính. Thay đổi trên dữ liệu các Branch không ảnh hưởng đến project chính và ngược lại. Vài vậy branch còn dc sd để theo dõi các thay đổi thử nghiệm bạn thực hiện đối với kho lưu trữ và có thể hoàn nguyên về các phiên bản cũ hơn.
  
  
  4. 
  
         
  
  
 
  
  
  
  
  
