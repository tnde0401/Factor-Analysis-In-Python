# Factor-Analysis-In-Python

## Giới thiệu

Báo cáo này trình bày phương pháp **Phân tích nhân tố** (Factor Analysis - FA), một kỹ thuật giảm chiều dữ liệu bằng cách mô hình hóa các biến quan sát thông qua các yếu tố tiềm ẩn (latent factors). Phương pháp này thường được sử dụng để khám phá cấu trúc tiềm ẩn trong dữ liệu lớn và giảm số lượng biến quan sát xuống ít hơn nhưng vẫn giữ được phần lớn thông tin ban đầu.

## Nội dung chính

### 1. Tổng quan về phân tích nhân tố
- Phân tích nhân tố giúp giảm số lượng biến quan sát phụ thuộc lẫn nhau thành một tập biến ít hơn.
- Phương pháp này tương tự như **Phân tích thành phần chính** (PCA) nhưng khác ở cách mô hình hóa các yếu tố tiềm ẩn.

### 2. Các phương pháp phân tích nhân tố
- **Phương pháp thành phần chính (Principal Component Method)**: Xác định các thành phần chính ảnh hưởng đến biến quan sát.
- **Phương pháp ước lượng hợp lý cực đại (Maximum Likelihood Estimation - MLE)**: Ước lượng tham số sao cho khả năng quan sát dữ liệu thực tế được tối đa hóa.

### 3. Xoay nhân tố
- Giới thiệu về các phương pháp xoay nhân tố vuông góc và không vuông góc để tìm cấu trúc dễ hiểu hơn từ các nhân tố.

### 4. Các loại phân tích nhân tố
- Phân tích nhân tố khám phá (Exploratory Factor Analysis - EFA) được sử dụng để xác định số lượng và mối quan hệ của các nhân tố tiềm ẩn trong tập hợp dữ liệu.
- Phân tích nhân tố khẳng định (Confirmatory Factor Analysis - CFA) nhằm xác thực các giả thuyết về mối quan hệ giữa các yếu tố và biến quan sát.

### 5. Ưu và nhược điểm của phân tích nhân tố
- Phương pháp phân tích nhân tố là một kỹ thuật mạnh mẽ trong thống kê, nhưng nó cũng có những ưu điểm và nhược điểm nhất định.

### 6. Phân tích nhân tố khám phá với Factor_analyzer trong Python

## Kết luận
Phân tích nhân tố là một công cụ mạnh mẽ trong xử lý dữ liệu đa chiều, đặc biệt hữu ích trong việc giảm chiều dữ liệu và khám phá các cấu trúc tiềm ẩn. Phương pháp này đã được áp dụng rộng rãi trong nhiều lĩnh vực như tâm lý học, xã hội học và kinh tế học.
