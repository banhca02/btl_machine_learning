# Bài Tập Lớn: Triển Khai Các Mô Hình Học Máy

Bài tập lớn của bạn sử dụng bộ dữ liệu Alzheimer’s Disease Dataset từ Kaggle để phát triển mô hình phân loại bệnh Alzheimer. Mục tiêu là xây dựng hệ thống tự động phân loại các giai đoạn của bệnh từ các đặc trưng như tuổi, giới tính, điểm MMSE và các chỉ số sức khỏe. Nhóm áp dụng các mô hình học máy như Logistic Regression, Decision Tree, và SVM để dự đoán một người có bị chẩn đoán suy giảm trí nhớ hay không, và so sánh kết quả của các mô hình đó.

## Dataset
[Alzheimer’s Disease Dataset](https://www.kaggle.com/datasets/rabieelkharoua/alzheimers-disease-dataset/data)

## Chạy Dự Án Đơn Giản Với Kaggle Notebook
[Machine Learning K22 Notebook](https://www.kaggle.com/code/huydeptrai1412/machine-learning-k22)

## Cài Đặt và Chạy Dự Án Machine Learning Tại Máy

### 1. Cài Đặt Python và Môi Trường

#### 1.1. Cài Python
Nếu máy tính chưa có Python, bạn có thể tải và cài đặt từ trang [Python Downloads](https://www.python.org/downloads/).  
Khuyến nghị chọn phiên bản Python 3.8 trở lên.

#### 1.2. Kiểm Tra Xem Máy Đã Có Venv Hay Chưa (Nếu Cần)
Để kiểm tra xem máy đã có `venv` hay chưa, mở terminal hoặc command prompt và chạy lệnh sau:
```bash
python -m venv --help

```

#### 1.3. Tạo môi trường ảo (khuyến khích)
Việc tạo một môi trường ảo giúp tách biệt các thư viện của dự án và không ảnh hưởng đến môi trường hệ thống.

Để tạo môi trường ảo, chạy lệnh:
```bash
python -m venv venv

```

Kích hoạt môi trường:
Windows:
```bash
.\venv\Scripts\activate

```

Mac/Linux:
```bash
source venv/bin/activate

```

### 2. Cài các thư viện cần thiết
```bash
pip install -r requirements.txt

```

### 3. Mở Jupyter Notebook
Để mở Jupyter Notebook, chạy:
```bash
jupyter notebook

```

### Thoát môi trường ảo
Để thoát môi trường ảo sau khi chạy xong
```bash
deactivate

```
