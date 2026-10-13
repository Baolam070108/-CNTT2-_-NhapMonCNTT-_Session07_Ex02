1. Phân tích

-Get-ChildItem: Tìm file hoặc thư mục theo tên, không tìm chữ bên trong file
-Select-String: Tìm nội dung hoặc từ khóa bên trong file
+An dùng sai lệnh vì muốn tìm lỗi trong nội dung log nhưng lại dùng lệnh tìm file

2. Sửa lỗi
-Dùng lệnh sau để tìm dòng chứa ERROR và hiển thị số dòng: Select-String -Path "access.log" -Pattern "ERROR"
