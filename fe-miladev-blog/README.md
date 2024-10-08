# Hướng dẫn chạy file Docker

Để chạy file Docker, bạn có thể làm theo các bước sau:

1. **Cài đặt Docker**:
    - Tải và cài đặt Docker từ trang chủ: [Docker](https://www.docker.com/get-started)

2. **Clone repository**:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

3. **Xây dựng Docker image**:
    ```sh
    docker build -t <image-name> .
    ```

4. **Chạy Docker container**:
    ```sh
    docker run -d -p 80:80 <image-name>
    ```

5. **Kiểm tra container đang chạy**:
    ```sh
    docker ps
    ```

6. **Truy cập ứng dụng**:
    - Mở trình duyệt và truy cập `http://localhost`

Lưu ý: Thay thế `<repository-url>`, `<repository-directory>`, và `<image-name>` bằng thông tin cụ thể của bạn.
