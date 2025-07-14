# Bus Ticket System

Hệ thống Bán Vé Xe Khách Trực tuyến là một nền tảng giúp khách hàng dễ dàng tìm kiếm, đặt vé và thanh toán vé xe khách. Hệ thống cũng hỗ trợ quản trị viên quản lý chuyến xe và vé một cách hiệu quả.

## Giới thiệu
Dự án này xây dựng một website đặt vé xe khách trực tuyến cho khách hàng, với giao diện thân thiện và tích hợp các tính năng hiện đại như tìm kiếm chuyến, chọn ghế, thanh toán trực tuyến, tích hợp cấc cổng thanh toán hiện đại như momo, vnpay,...

## Tính năng chính
- **Khách hàng**:
  - Tìm chuyến xe theo điểm đi, điểm đến, ngày giờ, nhu cầu khứ hầu, số vé.
  - Chọn ghế, hỗ trợ điểm đón - điểm trả nhiều tuyến đường, trung chuyển tận nơi, đặt vé nhanh chóng.
  - Thanh toán online qua cổng thanh toán hiện đại, thuận tiện, nhanh chóng: VNPay hoặc Momo.
  - Xem lịch sử đặt vé, đổi, hủy vé nhanh chóng.
  - Gửi yêu cầu hỗ trợ khi gặp sự cố, gửi feedback chuyến đi.
- **Quản trị viên**:
  - Quản lý lịch trình xe (thêm, sửa, xóa).
  - Theo dõi vé đã đặt và thông tin khách hàng.
  - Xem báo cáo doanh thu.

## Công nghệ sử dụng
- **Frontend**: React
- **Backend**: Java (Spring Boot 3, Spring Security)
- **Cơ sở dữ liệu**: MySQL
- **Thanh toán**: VNPay, Momo
- **Security**: JWT Token, phân quyền người dùng
- **Quản lý dự án**: maven, npm

## Logo công nghệ
 | Java (Spring Boot) | Spring Security | React | MySQL |
 |--------------------|-----------------|--------------|-------|
 ![Java](https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg) | ![Spring Security](https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg) | ![React](https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg) | ![MySQL](https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg) |

## Hướng dẫn cài đặt
### Yêu cầu
- Node.js (v16 trở lên)
- Java 17 (cho Spring Boot 3)
- MySQL (v8 trở lên)
- Yarn hoặc npm, maven

### Các bước cài đặt
1. **Clone dự án**:
   ```bash
   git clone https://github.com/QuocHuyLearningCode/bus-ticket-system.git
   cd bus-ticket-system
   ```

2. **Cài đặt**:
   - Frontend: dự án chạy trên [localhost:](http://localhost:5173/)
     ```bash
     cd frontend
     npm install
     npm run dev
     
     ```
   - Backend: [localhost:](http://localhost:8080/)
     ```bash
     cd backend
     down pom.xml
     
