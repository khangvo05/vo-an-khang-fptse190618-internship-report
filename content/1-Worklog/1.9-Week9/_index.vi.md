---
title: "Nhật ký công việc Tuần 9"
weight: 9
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu Tuần 9:
* Triển khai **MQTT Messaging** cho Dự án.
* Định nghĩa **Topic Hierarchy** (Hệ thống phân cấp Chủ đề).
* Mô phỏng **Data Publication** (Xuất bản Dữ liệu).

### Các nhiệm vụ thực hiện trong tuần này:
| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2   | - **Dự án:** Định nghĩa Cấu trúc **Topic** <br> - **Thực hành:** <br>&emsp; + Chốt các **topic** (ví dụ: `office/room1/temp`) | 11/03/2025 | 11/03/2025 | <https://docs.aws.amazon.com/iot/latest/developerguide/topics.html> |
| 3   | - **Dự án:** **Python MQTT Script** <br> - **Thực hành:** <br>&emsp; + Viết **Python script** sử dụng **`AWSIoTPythonSDK`** <br>&emsp; + Cấu hình **script** bằng **Certificates** từ Tuần 6 | 11/04/2025 | 11/04/2025 | <https://github.com/aws/aws-iot-device-sdk-python> |
| 4   | - **Dự án:** **Data Simulation** (Mô phỏng Dữ liệu) <br> - **Thực hành:** <br>&emsp; + Cập nhật **script** để **publish** dữ liệu **JSON** ngẫu nhiên | 11/05/2025 | 11/05/2025 | <https://www.youtube.com/watch?v=kYJj7K0fT4Y> |
| 5   | - **Dự án:** Xác minh Dữ liệu <br> - **Thực hành:** <br>&emsp; + Sử dụng **AWS Console MQTT Client** để **subscribe** tới **`office/*`** và theo dõi luồng dữ liệu | 11/06/2025 | 11/06/2025 | <https://docs.aws.amazon.com/iot/latest/developerguide/view-mqtt-messages.html> |
| 6   | - **Dự án:** **Threading** <br> - **Thực hành:** <br>&emsp; + Thêm logic **Threading** vào **Python script** để mô phỏng nhiều thiết bị | 11/07/2025 | 11/07/2025 | <https://www.geeksforgeeks.org/python/multithreading-python-set-1/> |

### Kết quả Tuần 9:
* Đã định nghĩa một **topic hierarchy** **MQTT** logic cho **Smart Office**.
* Đã tạo một **Python script** để mô phỏng các **hardware sensor**.
* Đã **publish** thành công **telemetry data** tới **AWS IoT Core**.