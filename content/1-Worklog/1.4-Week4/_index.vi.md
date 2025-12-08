---
title: "Nhật ký công việc Tuần 4"
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu Tuần 4:
* Giới thiệu về Điện toán phi máy chủ (Serverless Computing - Lambda).
* Hiểu về Kiến trúc hướng sự kiện (Event-Driven Architecture).
* Đào sâu kiến thức về Mạng (Private Subnets/NAT).

### Các nhiệm vụ thực hiện trong tuần này:
| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2   | - Xem video về **<i>AWS Lambda</i>** <br> - **Thực hành:** <br>&emsp; + Tạo một Lambda function "Hello World" sử dụng Python <br>&emsp; + Kiểm thử function trong console | 09/29/2025 | 09/29/2025 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 3   | - Xem video về **<i>Lambda Triggers (Kích hoạt)</i>** <br> - **Thực hành:** <br>&emsp; + Cấu hình S3 để kích hoạt một Lambda function khi tải file lên (on upload)| 09/30/2025 | 09/30/2025 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> <br> <https://docs.aws.amazon.com/lambda/latest/dg/lambda-invocation.html> |
| 4   | - Xem video về **<i>API Gateway</i>** <br> - **Thực hành:** <br>&emsp; + Tạo một HTTP API đơn giản <br>&emsp; + Tích hợp API Gateway với Lambda | 10/01/2025 | 10/01/2025 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> <br> <https://000055.awsstudygroup.com/vi/3-create-single-page-app/3.3-create-api-with-api-gateway/> |
| 5   | - Ôn tập **<i>Mạng VPC (VPC Networking)</i>** <br> - **Thực hành:** <br>&emsp; + Tạo một Private Subnet (Ôn tập Lab 3) <br>&emsp; + Khởi chạy một instance trong Private Subnet | 10/02/2025 | 10/02/2025 | <https://000003.awsstudygroup.com/> |
| 6   | - Nghiên cứu các **<i>Khái niệm hướng sự kiện (Event-Driven concepts)</i>** <br> - **Thực hành:** <br>&emsp; + Vẽ một sơ đồ về cách một cảm biến IoT có thể kích hoạt một Lambda function | 10/03/2025 | 10/03/2025 | <https://aws.amazon.com/event-driven-architecture/> |

### Kết quả Tuần 4:
* Đã tạo và kiểm thử thành công các Lambda function bằng Python.
* Đã kích hoạt Lambda tự động thông qua các sự kiện S3.
* Đã "public" một Lambda function thông qua API Gateway.
* Đã củng cố các khái niệm về mạng VPC liên quan đến private subnets.