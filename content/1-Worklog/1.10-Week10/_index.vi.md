---
title: "Nhật ký công việc Tuần 10"
weight: 10
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu Tuần 10:
* Cấu hình **AWS IoT Rules Engine**.
* Tích hợp **IoT Core** với **EventBridge**.
* Lọc dữ liệu đến (**Filter incoming data**).

### Các nhiệm vụ thực hiện trong tuần này:
| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2   | - **Dự án:** **IoT Rules** <br> - **Thực hành:** <br>&emsp; + Viết câu lệnh **SQL** để chọn dữ liệu: <br> ví dụ `SELECT * FROM 'office/+/temp'` | 11/10/2025 | 11/10/2025 | <https://docs.aws.amazon.com/iot/latest/developerguide/iot-sql-reference.html> |
| 3   | - **Dự án:** Tạo **Rule** <br> - **Thực hành:** <br>&emsp; + Tạo một **IoT Rule** trong **Console** <br>&emsp; + Thiết lập **Action**: "Gửi tin nhắn đến **EventBridge**" | 11/11/2025 |11/11/2025  | <https://docs.aws.amazon.com/iot/latest/developerguide/eventbridge-rule.html> |
| 4   | - **Dự án:** Thiết lập **EventBridge** <br> - **Thực hành:** <br>&emsp; + Truy cập **EventBridge**, kiểm tra các sự kiện đến | 11/12/2025 | 11/12/2025 | <https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-iot-event.html> |
| 5   | - **Dự án:** **Event Pattern** (Mẫu sự kiện) <br> - **Thực hành:** <br>&emsp; + Tạo một **EventBridge Rule** với mẫu để khớp với Nhiệt độ cao (**High Temp** > 40C) | 11/13/2025 | 11/13/2025 | <https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-event-patterns.html> |
| 6   | - **Dự án:** Kiểm thử Tích hợp (**Testing Integration**) <br> - **Thực hành:** <br>&emsp; + **Publish** dữ liệu nhiệt độ cao qua **Python script** <br>&emsp; + Xác minh số lượng chỉ số (**Rule metric count**) của **Rule** tăng lên | 11/14/2025 | 11/14/2025 | <https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-monitoring.html> |

### Kết quả Tuần 10:
* Đã cấu hình **IoT SQL Rules** để lọc lưu lượng tin nhắn.
* Đã thiết lập tích hợp trực tiếp giữa **IoT Core** và **EventBridge**.
* Đã định nghĩa các **EventBridge patterns** để phát hiện bất thường "**Nhiệt độ cao**" (**"High Temperature"** anomalies).