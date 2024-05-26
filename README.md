# Demo Project
![333795558-ea14059e-7c90-4589-9e4d-da0cbdc0a18a](https://github.com/MinhFX/POS/assets/146899219/9a9274ef-214d-46c6-a414-d64d04d2cd92)
![333795564-3f38a0ba-b1cb-4bdb-9dfe-60c3b52021f9](https://github.com/MinhFX/POS/assets/146899219/67ef2831-62d0-4b99-9f9d-dfa560243f96)
![333795571-c1698fac-6ea4-4e68-9038-fa6c20bff80b](https://github.com/MinhFX/POS/assets/146899219/ec561309-9942-4e95-b107-d61c3621f911)
![333795570-ec64e0c8-488f-4b16-90ca-220dd499592b](https://github.com/MinhFX/POS/assets/146899219/ff5fa4f5-3138-4aa2-95d1-b0a47b187227)
![333795568-03b84766-6044-4c03-9cfc-44c2b5843381](https://github.com/MinhFX/POS/assets/146899219/fef44203-8c4d-4ec3-81f4-c94e569122a2)
![333795567-e2531f17-04fc-464e-80f4-353f889acaad](https://github.com/MinhFX/POS/assets/146899219/d593b1b2-e779-4944-8d14-067e5d56b976)
![333795565-e605df6e-91a7-4a0a-9172-47ec7cc2844e](https://github.com/MinhFX/POS/assets/146899219/a741156f-3a08-431c-a4d8-bab9cefda1c7)
![333795572-f9639dec-e8b8-4f82-854a-aa96404720a7](https://github.com/MinhFX/POS/assets/146899219/75e7bfc5-c3d5-4cdf-8cba-803a63eea6ed)  


Hãy cài SQLServer nếu bạn chưa có !!
Hãy cài MayPOS trong Folder được phép chỉnh sửa các tệp !!
Hãy cài MayPOS trong Folder được phép chỉnh sửa các tệp !!
Hãy cài MayPOS trong Folder được phép chỉnh sửa các tệp !!

Trước khi vào ứng dụng vui lòng thực hiện các bước sau:

# Tạo Database trong SQLServer
1. Tạo Database (để trống sau khi tạo)
2. Vào Folder có tên là Data (Folder nằm ở địa chỉ bạn cài đặt MayPOS)
3. Trong Folder Data có tệp Data.sql 
Vui lòng truy vấn tệp này đến Database của bạn vừa tạo !!

---------------------------------------------------------------------------------------

# Kết nối SQLServer 
1. Vào MayPOS.exe.config
2. Sửa kết nối tại địa chỉ này
connectionString="Data Source=localhost;Initial Catalog=MayPOS;Integrated Security=True" providerName="System.Data.SqlClient"

Note:
- Data Source = địa chỉ kết nối đến Server Name của bạn
- Catalog = tên Database cần kết nối của bạn

---------------------------------------------------------------------------------------
Sau khi thực hiện các bước trên, hãy mở tệp MayPOS.exe để sử dụng

Chúc bạn cài đặt thành công !!

# Chú ý:  
Tài khoản đăng nhập
- Quyền quản trị:

Username: lychidung  
Password: 2005

- Quyền Staff:

Username: nguyendientriminh  
Password: 2005

Username: tranthanhphat  
Password: 2005

-------------------------
# Folder kiểm kê:
- BillLog: Lưu trữ Bill thống kê
- InvoiceLog: Lưu trữ các hóa đơn được xuất cho khách hàng

# Folder ảnh:
- avatar: Ảnh của các tài khoản Staff & Admin
- icon: Các icon có trong ứng dụng
- icon-theloai-mon: Các icon của danh mục món trong chức năng Order
- images: Ảnh thực đơn


# Liên hệ (3 người viết app):

https://www.facebook.com/chidung.ly.73/

https://www.facebook.com/nguyen.triminh.9889

https://www.facebook.com/trthphat
