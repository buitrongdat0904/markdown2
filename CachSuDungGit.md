# Một số câu lệnh trong Git
  
  ### init: Tạo một kho chứa Git
    git init

    > Nếu như bạn muốn theo dõi một dự án cũ trong Git, bạn cần ở trong thư mục của dự án đó. Lệnh này sẽ tạo một thư mục mới có tên .git, thư mục này chứa tất cả các tập tin cần thiết cho kho chứa.
  
  ### clone: Sao chép một kho chứa đã tồn tại 
  git clone https://github.com/username/Repositories_name
    > Câu lệnh trên sẽ tạo một thư mục mới có tên giống trên của Repo

  ### add : Sau khi bạn thay đổi source code: thêm mới, sửa, xoá files,… Bạn cần phải cập nhật lên Staging Area. Để cập nhật hết các files:
    git add . : thêm toàn bộ file
    git add file_name :thêm 1 file

        Sau lệnh add, bạn cần sử dụng câu lệnh Commit để đây thông tin thay đổi lên Local Respository:

   ### Commit: lưu trữ những thay đổi mà bạn thực hiện
        git commit -m "nd_commit" :

   ### Push: Gửi các thay đổi đến nhánh chính của kho lưu trữ từ xa của bạn
        1. git push origin master : gửi lên nhánh chính
        2. git push :gửi lên.
    
  ### Pull : Được sử dụng để thêm các thay đổi vào nhánh chính.
      git pull .

  ### log: Hiển thị ra 1 list các commit theo thứ tự thời gian gần nhất 
        git log
  ### status: liệt kê ra các file/folder nào có thay đổi
       git status
  
  ### Branch:là nhánh mà ở đó chúng ta sẽ lưu giữ các phiên bản cụ thể của project chính. Thay đổi trên dữ liệu các Branch không ảnh hưởng đến project chính và ngược lại. Vài vậy branch còn dc sd để theo dõi các thay đổi thử nghiệm bạn thực hiện đối với kho lưu trữ và có thể hoàn nguyên về các phiên bản cũ hơn.
    1. Tạo mới một Branch: git branch <name_branch> 
    2. Khiểm tra có bao nhiêu Branch: git branch 
          khi này thì nếu có dấu * xuất hiện trước tên branch nào thì con trỏ đang ở nhánh đó 
  ### Checkout : Chuyển đổi từ Branch này xang Branch khác
    git checkout <name_branch> hoặc git switch <name_branch>  
    Xoá 1 branch nào đó:** git checkout -d <name_branch> 

  ### Merge: sử dụng để gộp nhánh, gộp nhánh này vào nhánh khác.
     git merge <name_brance>: 

     > Khi gộp nhánh sẽ có hiện tượng xảy ra xung đột giữa các file/folder
      có sự thay đổi trong 1 nhánh hoặc nhiều nhánh nên có bao nhiêu file/folder
       xung đột thì mở ra để quyết định lấy nội dung nào trong file đó.
       
       VD: Ở đây file xung đột là 2.txt, mở ra thấy nội dung như sau:

      <<<<<<< HEAD
      Sua loi tren 1.txt
      =======
      Update new content to file
      >>>>>>> alpha
      nội dung xung đột nó đánh dấu bên trong các ký hiệu,
      
       nội dung nằm giữa <<<<<<< HEAD và ======= là nội dung có từ master,
        còn nội dung nằm giữa ======= và >>>>>>> alpha là nội dung từ alpha.
         Giữa hai nội dung đó lấy nội dung nào thì giữ, còn lại thì xóa hết.
          Ví dụ file trên giữ lại nội dung như sau (nội dung từ alpha)

  ### Revert : Sau khi sử dụng lệnh "git merge" để gộp nhánh mà muốn khôi khục lại nhánh trc thfi ta dùng lệnh này để quay lại trước khi gọp nhánh
   git merge "nd"



# Lệnh git cơ bản để upload một file lên GitHub.

### Khai báo
1. Nhập tên/gmai trong git bằng lệnh: *git config --global user.name "your_name"\ git config --global user.email "your_email"*.
        Trong đó *--global* được sử dụng để áp dụng cho tất cả các projects. Nếu bạn ko sử dụng --global thì settings sẽ chỉ dùng cho riêng project đó.
  
  ### 2. Lênh sao chép lại kho dữ liệu đã cso sẵn trên git từ trước: *
      git clone https://github.com/user/.............*
       Câu lệnh trên sẽ tạo một thư mục mới có tên giống trên của repo.
  
  ### 3.Lệnh cập nhật
     git add .  ----------> git commit -m "first commit"
          Sau khi thay đổi dữ liệu  source code: thêm mới, sửa, xoá files thì cần phải cập nhật lên Staging Area.
          Để cập nhật hết các files lên: $ git add .      
          Sau lệnh add, bạn cần sử dụng câu lệnh Commit để đây thông tin thay đổi lên Local Respository: git commit -m "Message"
  
  ### 4.Dẩy dữ liệu lên
    Git push 
    git pull 
  
  ## Sự khác biệt giữa user.name và credential
    -

   

