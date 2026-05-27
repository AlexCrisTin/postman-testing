# Báo Cáo Kiểm Thử API với Postman

## 1. Giới thiệu
- **Họ tên:**: Trần Ngọc An
- **MSSV:**: 23010283

## 2. Mục tiêu
Thực hành kiểm thử các API RESTful sử dụng công cụ Postman,
bao gồm các phương thức GET, POST, PUT, DELETE.

## 3. API được kiểm thử
Sử dụng API công khai: `https://jsonplaceholder.typicode.com`

## 4. Kết quả thực hiện

### 4.1. GET - Lấy danh sách bài viết
- **URL:** `GET /posts`
- **Kết quả:** Status 200 OK

![GET /posts](images/get-posts.png)

### 4.2. GET - Lấy bài viết theo ID
- **URL:** `GET /posts/1`
- **Kết quả:** Status 200 OK

![GET /posts/1](images/get-post-by-id.png)

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

![POST /posts](images/post-create.png)

### 4.4. PUT - Cập nhật bài viết
...

### 4.5. DELETE - Xóa bài viết
...

