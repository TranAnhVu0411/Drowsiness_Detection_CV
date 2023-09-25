# Tổng hợp code môn Computer Vision của nhóm 7
Thành viên:
- Nguyễn Trung Kiên: Đảm nhận train mô hình MTCNN + Video-SwinTransformer
- Trần Anh Vũ: Đảm nhận train mô hình Mediapipe + Inception Resnet + LSTM
- Võ Văn Quang: Đảm nhận train mô hình MTCNN + Inception ResNet + LSTM
- Trần Đức Thọ: Đảm nhận train mô hình Resnet + LSTM
- Phạm Hoàng Tùng: Đảm nhận train mô hình EfficientNet + LSTM

Bài toán: Nhận diện dấu hiệu buồn ngủ của tài xế

Bộ dữ liệu sử dụng SUST-DDD: 
- https://www.kaggle.com/datasets/esrakavalci/sust-ddd
- metadata chia fold: https://www.kaggle.com/datasets/vtrnanh/sust-ddd-metadata

Báo cáo có trong folder pdf

Lưu ý: 
- Các đoạn code trên phần lớn đều chạy trên Kaggle, cho nên có thể sẽ không chạy được trên local và Colab.
- Phần lớn các mô hình đều xử lý trực tiếp trên tập dữ liệu SUST-DDD, tuy nhiên có những mô hình cần dữ liệu tiền xử lý trước khi đi vào huấn luyện (những mô hình đó sẽ nằm trong folder và sẽ có 2 notebook riêng biệt, dành cho xử lý dữ liệu và dành cho huấn luyện mô hình)