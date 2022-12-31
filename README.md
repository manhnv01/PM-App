# PM-App
I. 	 Tổng quan về đề tài
1.	Giới thiệu đề tài
Sự bùng nổ thông tin và sự phát triển mạnh mẽ của công nghệ kỹ thuật số, yêu cầu muốn phát triển thì phải tin học hóa vào tất cả các ngành, các lĩnh vực. Các phần mềm giúp tiết kiệm một lượng lớn thời gian, công sức của con người, tăng độ chính xác và hiệu quả trong công việc. Một hệ thống giúp quản lý sản phẩm là không thể thiếu trong hoạt động kinh doanh. Hệ thống này chính là những phần mềm quản lý sản phẩm, giúp cho người dùng đặc biệt là các doanh nghiệp kiểm soát được hàng hóa một cách chặt chẽ hơn. 
Các doanh nghiệp phải quản lý một lượng lớn các sản phẩm. Công việc quản lý sản phẩm vào - ra, tồn kho, thông tin sản phẩm ngày càng khó khăn, Với việc lưu trữ và xử lý bằng thủ công thì sẽ tốn rất nhiều thời gian và nhân lực mà không đem lại hiệu quả cao. Đôi khi trong quá trình ghi chép có sai sót rất khó sửa chữa.
 “Phần mềm Quản lý sản phẩm trên thiết bị di động” là một giải pháp khắc phục. Hy vọng phần mềm này có thể giúp người quản lý theo dõi, tổ chức tốt các sản phẩm của mình. Và việc có thể cài đặt trên các thiết bị di động giúp việc quản lý thuận tiện hơn.

2.	Mục tiêu đề tài
Giúp người quản lý cài đặt ứng dụng Quản lý sản phẩm trên các thiết bị di động, quản lý thuận tiện, có thể theo dõi các sản phẩm mọi lúc, đạt các mục tiêu:
	- Quản lý các tài khoản đăng nhập.
- Quản lý nhập và xuất sản phẩm 
- Quản lý danh sách sản phẩm hiện có
- Quản lý thông tin sản phẩm
- Dùng Scan mã QR để nhập, xuất sản phẩm
3.	Yêu cầu
- Tính tiện dụng: Ứng dụng đơn giản, dễ sử dụng. Thiết kế mới, nhưng không cầu kì gây khó chịu cho người dùng.
- Tính đúng đắn: Ứng dụng chạy không lỗi.
- Tính thích nghi: Ứng dụng tương thích với nhiều loại thiết bị di động với cấu hình phần cứng cũng như thiết kế kiến trúc khác nhau.
- Tính tiến hóa: Ứng dụng dễ dàng cho việc phát triển thêm các tính năng mà không gây ảnh hưởng đến các tính năng đã phát triển trước.
II.	Phân tích và thiết kế hệ thống
1.	Sơ đồ tổng quát
![image](https://user-images.githubusercontent.com/88828150/210137733-2b9623bf-a295-4a12-84fb-94b1d4de6db4.png)

2.	Sơ đồ đăng nhập
![image](https://user-images.githubusercontent.com/88828150/210137754-09f28519-7b4b-4f8a-b962-1d06b0d5726b.png)

-	Đăng nhập:
+ Mô tả: Cho phép người dùng đăng nhập vào ứng dụng.
+ Đầu vào: Người sử dụng nhập thông tin tên tài khoản và mật khẩu, sau đó chọn “đăng nhập”

-	Quên mật khẩu:
+ Mô tả: Cho phép người dùng cấp lại mật khẩu mới, trong trường hợp có tài khoản nhưng quên mật khẩu.
+ Đầu vào: Nhập tên đăng nhập, chọn “tiếp tục”.

-	Đăng kí:
+ Mô tả: Giúp người dùng mới tạo tài khoản mới.
+ Đầu vào: Nhập tên đăng nhập, email, mã rerify được gửi về email bạn vừa nhập, mật khẩu mới, nhập lại mật khẩu mới và số điện thoại rồi chọn “đăng kí”.

 
3.	Sơ đồ quản lý sản phẩm
![image](https://user-images.githubusercontent.com/88828150/210137772-726b9fdb-033a-42bc-928d-4f872dd4704b.png)

-	 Thêm sản phẩm:
     + Mô tả: Giúp thêm thông tin sản phẩm.
+ Đầu vào: Điền đầy đủ thông tin sản phẩm bao gồm: Tên sản phẩm, mã sản phẩm, khối lượng, công ty sản xuất, nơi sản xuất, giá nhập, số lượng nhập và chọn ADD PRODUCT. Hoặc quét mã QR để thêm sản phẩm.

-	Xuất sản phẩm :
+ Mô tả: Giúp xuất sản phẩm.
+ Đầu vào: Điền đầy đủ thông tin sản phẩm xuất bao gồm: Mã sản phẩm, nơi nhận, giá xuất, số lượng xuất và chọn EXPORT. Hoặc quét mã QR để thêm sản phẩm

-	Xem danh sách sản phẩm:
+ Mô tả: Xem danh sách những sản phẩm đã có.
+ Đầu vào: Chọn danh sách xem, sẽ hiển thị danh sách sản phẩm đã thêm.

-	Xem chi tiết thông tin sản phẩm:
+ Mô tả: Giúp xem chi tiết các thông tin của từng sản phẩm hiện có.
+ Đầu vào: Chọn sản phẩm muốn xem thông tin chi tiết.

-	Xem danh sách sản phẩm đã thêm:
+ Mô tả: Xem danh sách những sản phẩm đã thêm.
+ Đầu vào: Chọn danh sách sản phẩm đã thêm, sẽ hiển thị danh sách sản phẩm đã nhập.

-	Xem danh sách sản phẩm đã xuất:
+ Mô tả: Xem danh sách những sản phẩm đã xuất.
+ Đầu vào: Chọn danh sách sản phẩm đã xuất, sẽ hiển thị danh sách sản phẩm đã xuất. 

-	Xem chi tiết thông tin sản phẩm đã thêm:
+ Mô tả: Giúp xem chi tiết các thông tin của từng sản phẩm đã thêm bao gồm thời gian xuất, tên sản phẩm, mã sản phẩm, khối lượng, công ty sản xuất, nơi sản xuất, giá nhập, số lượng nhập.
+ Đầu vào: Chọn sản phẩm muốn xem thông tin chi tiết.

-	Xem chi tiết thông tin sản phẩm đã xuất:
+ Mô tả: Giúp xem chi tiết các thông tin của từng sản phẩm đã xuất bao gồm: Thời gian xuất, tên sản phẩm, mã sản phẩm, khối lượng, công ty sản xuất, nơi sản xuất, giá xuất, số lượng xuất, nơi nhận.
+ Đầu vào: Chọn sản phẩm muốn xem thông tin chi tiết.

4.	Thư viện sử dụng

-	Thư viện huawei:
implementation 'com.huawei.agconnect:agconnect-core:1.5.2.300' implementation 'com.huawei.hms:hwid:5.3.0.302' 
implementation "com.huawei.agconnect:agconnect-auth:1.5.2.300" implementation 'com.huawei.agconnect:agconnect-cloud-database:1.4.8.300' 
implementation 'com.huawei.hms:scan:1.3.2.300'
-	Thư viện google
implementation 'com.google.android.material:material:1.4.0'
implementation platform('com.google.firebase:firebase-bom:28.1.0')
implementation 'com.google.firebase:firebase-analytics'
implementation 'com.journeyapps:zxing-android-embedded:4.2.0'
implementation 'com.squareup.picasso:picasso:2.5.2'

 
III.	 Thiết kế giao diện người dùng
1.	Màn hình đăng ký
![image](https://user-images.githubusercontent.com/88828150/210137700-c420c2bd-40b2-402c-ace5-c46c77b0616b.png)

2.	Màn hình đăng nhập
![image](https://user-images.githubusercontent.com/88828150/210137779-7f6c9472-c5af-447a-a135-3b3856cd9f6c.png)

3.	Màn hình quên mật khẩu
![image](https://user-images.githubusercontent.com/88828150/210137781-e04e5d47-350a-4687-938f-c3005751df20.png)

4.	Màn hình trang chủ
 ![image](https://user-images.githubusercontent.com/88828150/210137783-ddfce2ba-e25c-45c0-a26b-a35234bbd548.png)

5.	Màn hình thêm sản phẩm
![image](https://user-images.githubusercontent.com/88828150/210137789-3c03220f-66c8-42a0-8610-7a790b141e6d.png)

6.	Màn hình bán sản phẩm
![image](https://user-images.githubusercontent.com/88828150/210137795-02d1a4d9-0cca-4cff-bf4c-fd4efc329806.png)

7.	Màn hình danh sách sản phẩm
![image](https://user-images.githubusercontent.com/88828150/210137805-d1da552d-baa7-48e7-a966-438dc4a7c964.png)

8.	Màn hình chi tiết sản phẩm
![image](https://user-images.githubusercontent.com/88828150/210137812-cc6deb67-716f-4007-9c81-5ceff294d806.png)

9.	Màn hình lịch sử thêm sản phẩm
![image](https://user-images.githubusercontent.com/88828150/210137808-1071c5ae-0145-40c9-85a0-c2c497309ec9.png)

10.	Màn hình lịch sử xuất sản phẩm
![image](https://user-images.githubusercontent.com/88828150/210137825-3513074b-1e7e-4547-8b06-cc3f4ff5d1d3.png)

11.	Màn hình thông tin người dùng
![image](https://user-images.githubusercontent.com/88828150/210137827-5367e308-87d9-448c-ba0e-2e80405ba6ff.png)

12.	Màn hình hỗ trợ
![image](https://user-images.githubusercontent.com/88828150/210137819-70f86422-44a3-4b49-9dc4-b62387b89a2a.png)

13.	Màn hình hướng dẫn sử dụng
![image](https://user-images.githubusercontent.com/88828150/210137836-35602bac-5260-4585-9d91-b260fa9ee443.png)

14.	Màn hình đổi mật khẩu
![image](https://user-images.githubusercontent.com/88828150/210137839-bc7fba76-22fc-48ba-b0ae-f6017d4acec7.png)

15.	Màn hình đổi tên người dùng
![image](https://user-images.githubusercontent.com/88828150/210137923-36af3286-e486-44fb-b30b-ad5380ca3723.png)


IV.	Tổng kết
1.	Kết luận
-	Sản phẩm đạt được một số kết quả nhất định như:
o	Thêm, xuất sản phẩm
o	Xem danh sách sản phẩm đã có, đã thêm và đã xuất
o	Tính tổng tiền mỗi lần thêm/ xuất sản phẩm
o	Thời gian thêm và xuất sản phẩm chính xác
o	Giao diện dễ sử dụng, màu sắc hài hòa
o	Cài và sử dụng được trên hầu hết các phiên bản androi
o	Quét mã Qr để thêm, xuất sản phẩm nhanh hơn
2.	Hướng phát triển
- Nâng cấp, bổ sung thêm nhiều tính năng mới.
- Bảo mật chặt chẽ hơn.
- Cải tiến giao diện chuyên nghiệp hơn.

App: https://appgallery.huawei.com/#/app/C104686001
Medium:https://medium.com/@tranquynhtrang07062001/are-you-in-business-and-looking-for-a-product-management-software-full-featured-and-easy-to-use-932fb30f88e5
