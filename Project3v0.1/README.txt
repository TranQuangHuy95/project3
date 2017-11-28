Mục tiêu:thanh toán bằng tiền mặt
Khách hàng sẽ có 2 lựa chọn:
- Trường hợp thông thường khách hàng sẽ được cấp thẻ để thanh toán thay tiền mặt,
sau khi ăn xong sẽ trả lại thẻ và nhận lại tiền nếu thừa,
nếu khách hàng chưa trả lại thẻ và thẻ vẫn còn giá trị tiền thì giá trị được giữ trong những lần ăn sau trong vòng x tháng.
- Nếu khách hàng muốn tạo tài khoản:tài khoản chứa thông tin của khách hàng,
khách hàng sẽ được cấp 1 thẻ sử dụng vĩnh viễn,
tài khoản giúp khách hàng tích lũy giá trị thanh toán để được hưởng các ưu đãi,sử dụng nhiều thẻ trong cùng 1 tài khoản,đổi thẻ.

Giải thích:
Admin:quản lý hệ thống,có mọi quyền xem,thêm,xóa...
Staff:đứng quầy thanh toán

Hoạt động hệ thống:
1 máy tính làm server,đồng thời là máy admin dùng để đăng nhập và sử dụng hệ thống
1 máy làm máy quầy đăng kí
n máy làm quầy ăn(mô phỏng nên dùng 1 máy)

- Đầu tiên mở server(chạy Server.java)
- Mở quầy đăng kí và quầy ăn(chạy FoodStallMain.java,RegisterStallMain.java)
- RegisterStallController và FoodStallController thực hiện các hoạt động của quầy
- Mỗi quầy giao tiếp với server bằng luồng,server sẽ tạo n luồng để giao tiếp với n quầy,mỗi quầy cũng tạo 1 luồng để giao tiếp với server
- Các lớp Utils trong package Object để quản lý CSDL
- package Interface chứa các lớp giao diện:
	- AdminFrame chứa AdminPanel và LoginPanel,đăng nhập = LoginPanel,thành công thì chuyển sang AdminPanel
	- RegisterStallFrame chứa RegisterStallPanel và LoginPanel

Tham khảo các sơ đồ phân tích thiết kế(dùng astah)

Việc:
- Phần cứng
- Đọc tín hiệu vào Java
- CSDL
- Interface
- Giao tiếp server,client(tôi làm)
