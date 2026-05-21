CNN CIFAR10
    Sử dụng mạng CNN để phân loại ảnh.
    Dataset CIFAR10 gồm 10 lớp ảnh màu kích thước 32x32.
    Mô hình gồm:
    Conv2D
    MaxPooling
    Flatten
    Dense
    Hàm kích hoạt ReLU.
    Softmax dùng cho phân loại nhiều lớp.
RNN Bitcoin
    Dùng RNN để dự đoán chuỗi thời gian.
    Input là giá Bitcoin 30 ngày trước.
    Output là giá ngày tiếp theo.
    Dữ liệu được chuẩn hóa bằng MinMaxScaler.
    Hàm loss dùng Mean Squared Error.