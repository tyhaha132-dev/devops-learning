1. Chmod 644 file.txt có nghĩa là owner có thể đọc và viết file.txt còn group và other thì chỉ có thể viết.
2. ls -l không đủ để biết file có chạy được không là bởi vì nó chỉ cho biết quyền của từng nhóm . Nếu muốn biết bạn có thể chạy file đó được hay không thì bạn phải xác định mình thuộc nhóm nào rồi sau đó xem quyền mình có được truy xuất hay không.
3. Tại vì r chỉ có quyền đọc còn x nó là quyền truy xuất , quyền đi qua tức là bạn có thể truy cập vào các mục bên trong khi biết tên . Quyền r bạn có thể liệt kê tên file bên trong nhưng quyền x bạn mới có thể truy cập vào 
