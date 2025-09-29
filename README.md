🏨 Hotel Management System
Semester: FALL 2025
Duration: 10 weeks
Group: 3 Students
Total Marks: 10
📖 Mô tả dự án

Hệ thống quản lý khách sạn, phục vụ các nghiệp vụ hằng ngày:

Đăng ký & đặt phòng (Guest registration & booking)

Kiểm tra & phân bổ phòng (Room availability & allocation)

Quản lý Check-in / Check-out

Quản lý dịch vụ đi kèm (restaurant, spa, laundry, …)

Thanh toán & xuất hóa đơn

Báo cáo doanh thu & thống kê cho quản lý

👉 Yêu cầu: Hệ thống vận hành trơn tru, không double-booking, tính phí chính xác, hỗ trợ báo cáo thống kê phân tích.

👥 Vai trò & Phân công
🎓 Student 1 – Guest & Administrator

Guest

Tìm phòng trống theo ngày/loại phòng

Đặt phòng

Yêu cầu thêm dịch vụ

Thanh toán khi checkout

Administrator

Quản lý tài khoản nhân viên

Cấu hình hệ thống (thuế, loại dịch vụ, …)

🎓 Student 2 – Receptionist & Manager

Receptionist

Tạo / cập nhật / hủy đặt phòng

Quản lý check-in / check-out

Xuất hóa đơn

Phân bổ phòng

Manager

Xem báo cáo doanh thu (ngày/tháng/năm)

Top 10 khách hàng thường xuyên

Dịch vụ được dùng nhiều nhất

Tỷ lệ sử dụng phòng, thống kê hủy

🎓 Student 3 – Service Staff & Housekeeping

Service Staff

Ghi nhận dịch vụ khách sử dụng (ăn uống, spa, giặt ủi, …)

Cập nhật trạng thái dịch vụ

Xuất các báo cáo dịch vụ

Housekeeping Staff

Cập nhật trạng thái phòng (sạch, bẩn, bảo trì)

Báo cáo vệ sinh, bảo trì, hiệu suất nhân viên

📌 Business Rules

Mỗi phòng chỉ được đặt bởi một khách tại một thời điểm (không double-booking).

Phòng phải sạch & trống trước khi giao cho khách.

Thanh toán = tiền phòng + dịch vụ + thuế.

Đặt phòng phải có ngày check-in và check-out.

Nếu hủy sau ngày check-in → bị tính phí phạt.

Hóa đơn luôn được xuất khi checkout.

Dịch vụ phải gắn với một booking cụ thể.

Booking chỉ check-in khi có đảm bảo thanh toán (cọc/thẻ tín dụng).

🛠️ Cách làm việc với GitHub (NetBeans 13)
1. Clone project lần đầu

Mở NetBeans 13

Vào Team → Git → Clone…

Nhập URL repo:

https://github.com/<team-name>/hotel-management-system.git


Nếu repo private → nhập GitHub username + token làm password

Chọn thư mục lưu → Finish

2. Pull code mới nhất

Chuột phải vào project → Git → Remote → Pull…

Chọn branch (thường là main) → Finish

Code trên GitHub sẽ cập nhật về máy

3. Commit & Push code

Chuột phải vào project → Git → Commit…

Chọn file cần commit

Nhập message mô tả

Bấm Commit

Sau đó: Chuột phải vào project → Git → Remote → Push…

Chọn branch (ví dụ: student1-guest) → Finish

4. Làm việc theo branch riêng (khuyến nghị)

Chuột phải vào project → Git → Branch/Tag → Create Branch…

Đặt tên branch:

student1-guest

student2-receptionist

student3-service

Mỗi người làm trên branch riêng, push branch của mình.

Người quản lý sẽ merge vào main.
