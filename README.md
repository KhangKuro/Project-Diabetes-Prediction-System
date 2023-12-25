

<img src="https://github.com/KhangKuro/Project-Diabetes-Prediction-System/blob/main/picture.png" />


# Diabetes Prediction System - Dự Đoán Bệnh Tiểu Đường

## Mục Đích

Dự án này nhằm xây dựng một hệ thống dự đoán bệnh tiểu đường dựa trên các thông số chẩn đoán và bộ dữ liệu thu thập từ Kaggle. Bằng việc sử dụng các kỹ thuật phân tích dữ liệu và mô hình hóa, chúng tôi đã thực hiện một loạt các bước để xử lý dữ liệu và xây dựng mô hình dự đoán.

## Nội Dung

### 1. Load the Dataset - Đọc Bộ Dữ Liệu

Nguồn bộ dữ liệu: [Kaggle](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)

### 2. Exploratory Data Analysis - Phân Tích Tổng Quát Dữ Liệu

Bộ dữ liệu này được lấy từ Viện Quốc Gia về Bệnh Tiểu Đường và các bệnh về tiêu hóa và thận. Mục tiêu là dự đoán dựa trên các phép đo chẩn đoán xem một bệnh nhân có bị tiểu đường hay không. Tất cả bệnh nhân đều là nữ từ 21 tuổi trở lên ở Ấn Độ.

Có tổng cộng 9 cột tương ứng với 9 thông tin (biến) như sau:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome

Bộ dữ liệu không có giá trị bị thiếu. Tuy nhiên, cần tiền xử lý dữ liệu để thay thế các giá trị bằng 0.

### 3. Data Visualization - Trực Quan Hóa Dữ Liệu

#### 3.1 Đồ thị Boxplot

Biểu đồ boxplot thể hiện vị trí phân bố của dữ liệu từng biến trong bộ dữ liệu.

#### 3.2 Biểu Đồ Cột và Đường Cong Ước Lượng

Đường cong ước lượng của mỗi biến thể hiện phân phối của biến đó.

### 4. Data Pre-processing - Tiền Xử Lý Dữ Liệu

#### 4.1 Xử Lý Giá Trị Thiếu

Cần thay thế các giá trị bằng 0 trong bộ dữ liệu.

#### 4.2 Xử Lý Mất Cân Bằng Dữ Liệu

Cần xử lý mất cân bằng dữ liệu trong quá trình xây dựng mô hình Machine Learning.

### 5. Model Building - Xây Dựng Mô Hình

#### 5.1 Chia Dữ Liệu và So Sánh Mô Hình

Sử dụng các thuật toán khác nhau và so sánh hiệu suất của chúng.

#### 5.2 Chọn Mô Hình

Sử dụng Decision Tree với hiệu suất cao nhất.

### 6. Review - Đánh Giá Mô Hình

#### 6.1 Classification Report

Đánh giá kết quả mô hình dự đoán.

#### 6.2 Confusion Matrix

Hiển thị kết quả dự đoán của mô hình trên ma trận nhầm lẫn.

---

Cảm ơn bạn đã đọc. Đừng ngần ngại đóng góp ý kiến hoặc thêm thông tin vào dự án!
Special thanks to LinhChiHo for their invaluable guidance and insights throughout the development of this project!
