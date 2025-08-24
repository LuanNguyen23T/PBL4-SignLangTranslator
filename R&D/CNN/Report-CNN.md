# Báo cáo Convolutional Neural Network

## Mục lục
- [Giới thiệu](#giới-thiệu)
- [Kiến trúc mô hình](#kiến-trúc-mô-hình)

## Giới thiệu
- CNN ra đời để giảm số lượng tham số và khai thác đặc trưng cục bộ ảnh (cạnh, góc, viền,...)
- Pixel gần nhau có thông tin tương đồng so với các pixel ở xa

## Kiến trúc mô hình 

### 1. Convolutional Layer
- Thực hiện phép convolutional cho ảnh với các kernel 
- Mỗi kernel sẽ học một đặc trưng khác nhau

![Các Kernel và học đặc trưng tương ứng](CNN/Photos/Kernel.png)

![Phép tính Convolutional](CNN/Photos/Phep-tinh-Convolutional.png)

### 2. Pooling layer
- Giảm kích thước để giảm tính toán nhưng vẫn giữ đặc trưng quan trọng
- Hai loại chính: Max pooling & Average pooling

![Pooling Layer](CNN/Photos/Pooling-Layer.png)


### 3. Fully Connected Layer
- Sau nhiều lớp conv + pooling, dữ liệu được chuyển thành vector cuối có kích thước (X, 1)
- Các FCL kết hợp đăch trưng để phân loại

![Fully Connected Layer](CNN/Photos/FLC.png)



