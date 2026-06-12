[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/rBNuyfdi)

# 📚 TrekMate Danang — Tìm bạn đi bộ đường dài

Nền tảng quản lý và hỗ trợ tìm kiếm tour đi bộ đường dài tại Đà Nẵng, giúp kết nối người dẫn đoàn và khách hàng, tích hợp thuê đồ tự động và trợ lý AI tư vấn, được phát triển theo mô hình Research By Learning (RBL) với hàm lượng nghiên cứu chuyên sâu về thuật toán và kiến trúc hệ thống.

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | Reactjs |
| **Backend** | Java Spring Boot |
| **Database** | SQL Sever |
| **Auth** | JWT + Refresh Token, Google OAuth |
| **Storage** | Cloudinary |
| **Payment** | PayOS |
| **AI** | Google Gemini |
| **Research** | 10-50 IEEE/Springer Papers, RBL Methodology |

---

## 📋 Yêu Cầu Cài Đặt

- [Java](https://nodejs.org/)
- [Reactjs](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Docker Desktop](https://www.docker.com/products/docker-desktop/) (cho PostgreSQL)
- [Git](https://git-scm.com/)

---

## 🔬 Hàm Lượng Nghiên Cứu (RBL)

Dự án này áp dụng phương pháp Research By Learning, tập trung vào các trụ cột:

Business Intelligence: Giải quyết bài toán tối ưu hóa lộ trình di chuyển (Routing) và gợi ý lịch trình tour cá nhân hóa thông qua thuật toán Thuật toán di truyền (Genetic Algorithm).

Công nghệ & Kiến trúc: 
    Triển khai kiến trúc Microservice hoặc Clean Architecture / Hexagonal Architecture với Java Spring Boot để đảm bảo tính mở rộng (Scalability).
    Tối ưu hóa hiệu năng hệ thống thông qua cơ chế Caching (Redis) giúp giảm tải cho SQL Server khi truy vấn các tour phổ biến.
    Tích hợp kỹ thuật RAG (Retrieval-Augmented Generation) kết hợp với Google Gemini API để xây dựng trợ lý AI có khả năng tư vấn tour chính xác dựa trên dữ liệu thời gian thực của TrekMate thay vì chỉ trả lời chung chung.

Học thuật: Tổng hợp, phân tích và áp dụng lý thuyết từ danh mục 50 bài báo khoa học uy tín (IEEE, Springer...) về các chủ đề: Smart Tourism Integration, Automated Inventory Management Systems, và AI-driven Personalized Recommendation.

---

## ⚡ Hướng Dẫn Cài Đặt & Chạy

### Bước 1: Clone repo

```bash
git clone https://github.com/SU26SWR302/research-by-learning-project-swd392_group4.git
cd [Ten-Thu-Muc-Du-An]
```

### Bước 2: Cấu hình Backend
```bash

cd backend
# Cấu hình file environment/application.properties
# Chạy dự án
mvn spring-boot:run
```
### Bước 3: Cấu hình Frontend
```bash

cd frontend
npm install
npm run dev
```

## 📁 Cấu Trúc Dự Án
```
project-root/
├── docs/
│   ├── HighLevelDesign.pdf     # Tài liệu thiết kế hệ thống
│   ├── RDS_History/            # File RDS cập nhật tiến độ theo nhóm
│   └── research-papers/        # 10-50 Papers (IEEE, Springer...)
├── src/
│   ├── backend/                # Mã nguồn Backend
│   └── frontend/               # Mã nguồn Frontend
├── slides/                     # Slide báo cáo cuối kỳ (từ file Design)
└── README.md                   # File này
```

## 👥 Vai Trò Người Dùng

| Role | Quyền |
|------|-------|
| **Student** | Xem/mua khóa học, xem video, làm bài tập, nhận AI feedback |
| **Instructor** | Tạo/sửa/xóa khóa học, thêm bài giảng & bài tập |
| **Admin** | Duyệt giảng viên, quản lý hệ thống |

---

### 📑 Tài liệu liên quan
Link Jira: https://tranquanghuyit101.atlassian.net/jira/software/projects/KAN/boards/2?atlOrigin=eyJpIjoiY2Q3MDNiNWMyMjk3NDZkMTgwN2Y4YzFjZWU0YzEwZjEiLCJwIjoiaiJ9

High-level Design: 

Slides Báo cáo: 

Paper: https://www.overleaf.com/read/wkhtfzrcbmnh#da960f

Video Demo (nếu có):