- index ex_options

Theo như e hiểu đây là trang show các discounts dành cho rounding cuối cùng hoặc rounding mới
Trang index sẽ:
  + show ra các list discounts
  + thêm các discount mới

  Discount đang giới hạn chỉ tạo được 20 discounts mới
  Hiện tại đang hiện build sẵn 20 discounts mới, và dùng javascript để ẩn nó đi.Khi nhấn nút thì mới hiện ra 
  Nếu không muốn fix cứng 20 discounts thì có thể dùng gem cocoon sử dụng nested form để tùy biến discounts sử dụng hoặc tự viết js cho việc nested form

  Rounding sẽ có chức năng như: Làm tròn bằng tay, làm tròn tự động 
  Discount sẽ có các mục như: thứ tự sắp xếp, thể loại, tên discount, value, ứng dụng giảm giá, xóa

- create ex_options

Tạo ra 1 rounding mới, đồng thời tạo ra các discounts của nó
Khi submit thành công, tạo rounding và các discount của rounding vừa submit. Redirect về trang locahost:3000/exOptionSetup


- update ex_options

Update chức năng của rounding cuối cùng và các discount của nó 
Khi submit thành công, tạo route và các discount của route vừa submit. Redirect về trang locahost:3000/exOptionSetup
