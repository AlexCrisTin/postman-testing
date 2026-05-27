# Báo Cáo Kiểm Thử API với Postman

<img width="1587" height="988" alt="Screenshot 2026-05-27 162258" src="https://github.com/user-attachments/assets/5fdb4a2e-5058-4e08-b68b-05fa52217679" />


## 1. Giới thiệu
- **Họ tên:** Trần Ngọc An
- **MSSV:** 23010283

## 2. Mục tiêu
Thực hành kiểm thử các API RESTful sử dụng công cụ Postman,
bao gồm các phương thức GET, POST, PUT, DELETE.

## 3. API được kiểm thử
Sử dụng API công khai: `https://jsonplaceholder.typicode.com`

## 4. Kết quả thực hiện

### 4.1. GET - Lấy danh sách bài viết
- **URL:** `GET /posts`
- **Kết quả:** Status 200 OK
- 
<img width="1588" height="995" alt="image" src="https://github.com/user-attachments/assets/aede88b5-028f-4fd9-932f-1d88939874ef" />

### 4.2. GET - Lấy bài viết theo ID
- **URL:** `GET /posts/1`
- **Kết quả:** Status 200 OK

<img width="1578" height="992" alt="image" src="https://github.com/user-attachments/assets/2423cd3f-504f-4b36-96d4-f15fd7758af9" />


### 4.3. POST - Tạo bài viết mới
- **URL:** `POST /posts`
- **Body:**
```json
{
  "title": "Bài viết test",
  "body": "Nội dung test",
  "userId": 1
}
```
- **Kết quả:** Status 201 Created

<img width="1589" height="996" alt="image" src="https://github.com/user-attachments/assets/34051742-d45a-4684-bd22-23bb45350f16" />


### 4.4. PUT - Cập nhật bài viết

<img width="1585" height="998" alt="image" src="https://github.com/user-attachments/assets/9f78f818-d3cb-4e8b-87e0-46378e96e474" />


### 4.5. DELETE - Xóa bài viết

<img width="1577" height="993" alt="image" src="https://github.com/user-attachments/assets/9ea1b829-0047-47ca-b894-9ba51d7ab559" />


