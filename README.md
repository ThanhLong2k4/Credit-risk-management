# Credit-risk-management
 Dự án này tập trung vào việc xây dựng các mô hình dự đoán khả năng khách hàng vỡ nợ, bao gồm mô hình scorecard truyền thống . Dự án bao gồm các bước khám phá dữ liệu, xử lý biến, lựa chọn đặc trưng và đánh giá mô hình.

## 🔍 Khám phá Dữ liệu (EDA) sử dụng R

-Tập dữ liệu được lấy trên Kaggle
- Để dữ liệu sử dụng không bị mất cân bằng, dữ liệu được xử lý bằng phương pháp oversampling và undersampling

## 🧮 Xây dựng Mô hình Scorecard Tín dụng

- Thực hiện **binning** các biến đầu vào.
- Tính **WOE (Weight of Evidence)** cho các bin và sử dụng WOE làm đầu vào cho mô hình.
- Huấn luyện mô hình **logistic regression** và **Random Tree** trên các biến đã WOE.
- Dựa vào các chỉ số Accuracy cho thấy độ chính xác của mô hình 
