---
title: "Nhật ký công việc Tuần 1"
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

### Mục tiêu Tuần 1:
* Lập nhóm cho dự án và tìm hiểu các quy định của workshop.
* Thiết lập môi trường AWS bảo mật (Account & IAM).
* Học và thực hành các dịch vụ cốt lõi: VPC, EC2, và Lambda.

### Các nhiệm vụ thực hiện trong tuần này:
| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2   | - **Công tác chuẩn bị (Logistics):** <br>&emsp; + Gặp gỡ các thành viên trong nhóm và trao đổi liên lạc <br>&emsp; + Đọc các chính sách và hướng dẫn của workshop <br>&emsp; | 09/08/2025 | 09/08/2025 | <https://policies.fcjuni.com> <br> |
| 3   | - **Thiết lập tài khoản:** <br>&emsp; + Tạo tài khoản AWS Free Tier <br>&emsp; + Kích hoạt xác thực đa yếu tố (MFA) <br>&emsp; + Tạo Billing Alarm (Quan trọng để kiểm soát chi phí) | 09/09/2025 | 09/09/2025 | <https://000001.awsstudygroup.com/> |
| 4   | - **Cơ bản về Mạng (VPC):** <br>&emsp; + Tạo một **VPC** (Virtual Private Cloud) tùy chỉnh <br>&emsp; + Tạo một **Public Subnet** <br>&emsp; + Gắn một **Internet Gateway** (IGW) để cho phép truy cập internet | 09/10/2025 | 09/10/2025 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> <br> <https://000003.awsstudygroup.com/> |
| 5   | - **Cơ bản về Tính toán (EC2):** <br>&emsp; + Khởi chạy một **EC2 Instance** (Linux t2.micro) vào Public Subnet của bạn <br>&emsp; + Kết nối tới instance sử dụng Instance Connect hoặc SSH | 09/11/2025 | 09/11/2025 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> <br> <https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html> |
| 6   | - **Cơ bản về Serverless (Lambda):** <br>&emsp; + Tạo một **Lambda Function** "Hello World" đơn giản <br>&emsp; + Kiểm thử (Test) function thủ công trong console | 09/12/2025 | 09/12/2025 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> <br> <https://docs.aws.amazon.com/lambda/latest/dg/welcome.html> |

### Kết quả Tuần 1:
* Đã lập nhóm thành công và xem lại các giao thức của workshop.
* Đã bảo mật AWS Root User với MFA và thiết lập cảnh báo thanh toán (billing alerts).
* Đã xây dựng một mạng nền tảng (VPC) từ đầu.
* Đã khởi chạy và truy cập một máy chủ ảo (EC2).
* Đã thực thi một serverless function (Lambda) thành công.