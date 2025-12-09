---
title: "Nhật ký công việc Tuần 6"
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu Tuần 6:
* **KHỞI ĐỘNG DỰ ÁN: Test IoT**
* Thiết lập Môi trường **AWS IoT Core**.
* Đăng ký **IoT Things** (Thiết bị mô phỏng - Simulated Devices).

### Các nhiệm vụ thực hiện trong tuần này:
| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2   | - **Dự án:** Giới thiệu về AWS IoT Core <br> - **Thực hành:** <br>&emsp; + Đăng nhập vào **AWS Console** -> **IoT Core** <br>&emsp; + Tạo một **"Thing Type"** cho các **Smart Sensor** | 10/13/2025 | 10/13/2025 | <https://docs.aws.amazon.com/iot/latest/developerguide/iot-thing-management.html> |
| 3   | - **Dự án:** Đăng ký "Things" <br> - **Thực hành:** <br>&emsp; + Tạo một **Thing** đơn lẻ (ví dụ: "OfficeTempSensor1") <br>&emsp; + Tải xuống **certificates** và **keys** | 10/14/2025 | 10/14/2025 | <https://docs.aws.amazon.com/iot/latest/developerguide/create-iot-resources.html> |
| 4   | - **Dự án:** **IoT Policies** <br> - **Thực hành:** <br>&emsp; + Tạo một **IoT Policy** cho phép **Connect**, **Publish**, **Subscribe** <br>&emsp; + Đính kèm **Policy** vào **Certificate** | 10/15/2025 | 10/15/2025 | <https://docs.aws.amazon.com/iot/latest/developerguide/iot-policies.html> |
| 5   | - **Dự án:** Kiểm tra kết nối thiết bị (**Device Connection Test**) <br> - **Thực hành:** <br>&emsp; + Sử dụng **MQTT Test Client** trong **Console** để mô phỏng một thiết bị kết nối | 10/16/2025 | 10/16/2025 | <https://docs.aws.amazon.com/iot/latest/developerguide/view-mqtt-messages.html> |
| 6   | - **Dự án:** Tài liệu hóa (**Documentation**) <br> - **Thực hành:** <br>&emsp; + Ghi lại **Thing ARN** và **Certificate ID** trong ghi chú dự án | 10/17/2025 | 10/17/2025 | |

### Kết quả Tuần 6:
- Test thành công những điều sau: 
* Đã khởi tạo thành công môi trường **AWS IoT Core**.
* Đã đăng ký **"Thing"** đại diện cho các **sensor** văn phòng.
* Đã tạo và đính kèm các **IoT Policies** bảo mật.
* Đã xác minh kết nối cơ bản bằng **MQTT Test Client**.