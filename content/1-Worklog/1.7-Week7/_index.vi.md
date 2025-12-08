---
title: "Nhật ký công việc Tuần 7"
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu Tuần 7:
* **Chuẩn bị Giữa kỳ (Trụ cột 1):** Nắm vững các Kiến trúc Bảo mật (**IAM, KMS, WAF, Shield, Secrets Manager**).
* **Chuẩn bị Giữa kỳ (Trụ cột 2):** Nắm vững các Kiến trúc Đàn hồi (**Multi-AZ, Auto Scaling, Route 53**).
* **Bảo trì Dự án:** Áp dụng các khái niệm bảo mật cơ bản vào thiết lập IoT (Khái niệm).

### Các nhiệm vụ thực hiện trong tuần này:
| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2   | - **Ôn tập Thi (Bảo mật):** <br>&emsp; + Tìm hiểu sâu về **IAM** (Policies, Roles, MFA) và **SCP** (**Service Control Policies**) <br>&emsp; + Nghiên cứu cơ bản về **Mã hóa (Encryption)**: **KMS** (**Key Management**) và **TLS/ACM** | 10/20/2025 | 10/20/2025 | <https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html> <br> <https://000033.awsstudygroup.com/vi/1-introduce/> |
| 3   | - **Ôn tập Thi (Bảo mật Mạng):** <br>&emsp; + So sánh **Security Groups** và **NACLs** (**Stateful** vs **Stateless**) <br>&emsp; + Ôn tập Bảo mật Biên: **AWS WAF**, **Shield**, và **GuardDuty** | 10/21/2025 | 10/21/2025 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> <br> <https://aws.amazon.com/waf/> <br> <https://tutorialsdojo.com/security-group-vs-nacl/>|
| 4   | - **Ôn tập Thi (Tính đàn hồi - Resilience):** <br>&emsp; + Nghiên cứu **Tính sẵn sàng cao (HA)** và **Phục hồi sau thảm họa (DR)** <br>&emsp; + Ôn tập **Auto Scaling Groups** (Launch Templates) và **Load Balancing** (ALB/NLB) | 10/22/2025 | 10/22/2025 | <https://docs.aws.amazon.com/wellarchitected/latest/reliability-pillar/welcome.html> <br> <https://viblo.asia/p/auto-scaling-group-tren-aws-EbNVQrxB4vR> |
| 5   | - **Ôn tập Thi (Độ tin cậy Mạng):** <br>&emsp; + Tìm hiểu sâu về **Route 53** (Các chính sách Định tuyến: Simple, Weighted, Failover) <br>&emsp; + Nghiên cứu các chiến lược **Backup & Restore** (khái niệm **RTO/RPO**) | 10/23/2025 | 10/23/2025 | <https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html> <br> <https://aws.amazon.com/blogs/architecture/disaster-recovery-dr-architecture-on-aws-part-ii-backup-and-restore-with-rapid-recovery/> |
| 6   | - **Thi Thử:** <br>&emsp; + Làm bài quiz ôn tập tập trung vào "**Security**" và "**Reliability**" <br>&emsp; + **Ôn tập:** Đọc lại ghi chú về **Secrets Manager** và **Parameter Store** | 10/24/2025 | 10/24/2025 | |

### Kết quả Tuần 7:
* Đã nắm vững sự khác biệt giữa các **firewall Stateful (SG)** và **Stateless (NACL)**.
* Đã hiểu cách thiết kế kiến trúc chống lỗi bằng **Multi-AZ** và **Auto Scaling**.
* Đã làm quen với các dịch vụ bảo mật nâng cao (**GuardDuty, WAF, KMS**).
* Đã ôn tập các chiến lược **Phục hồi sau thảm họa (Disaster Recovery)** quan trọng.