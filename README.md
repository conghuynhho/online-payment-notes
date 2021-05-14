# ONLINE PAYMENT PROJECT

### Mục tiêu đề tài:
Sử dụng máy học để phân loại các cá nhân thành một trong bốn loại loại dịch vụ tài chính (dịch vụ thanh toán) mà họ có nhiều khả năng sử dụng nhất. Hay nói cách khác là phân loại các cá nhân có sử dụng **mobile payment** không.

### Phương pháp kĩ thuật (thuật toán)
- Có một số lượng lớn các thuật toán học máy có thể được áp dụng cho các bài toán phân loại nhiều lớp, bao gồm mạng nơ-ron, thuật toán di truyền và cây quyết định.
- Support Vector Machines, Decision Tree Classifiers, Random Forest Classifiers, k-Nearest-Neigbours, Gaussian Naive Bayes and Logistic Regression đều được sử dụng rộng rãi cho các vấn đề có các tham số tương tự. Máy hỗ trợ Vector có lợi thế là chúng có thể xử lý số lượng lớn các tính năng.
### Dataset 
- Dataset được lấy từ [trang][datasetLink] sau được tạo bởi Zindi
- **trainning data** bao gồm **36** thuộc tính và **7.100** records.
- 4 loại dịch vụ được phân loại sẽ là: 
  - **0. No_financial_services:** Những cá nhân không sử dụng tiền di động, không tiết kiệm, không có tín dụng và không có bảo hiểm
  - **1. Other_only:** Cá nhân không sử dụng tiền di động nhưng sử dụng ít nhất một trong các dịch vụ tài chính khác (tiết kiệm, tín dụng, bảo hiểm)
  - **2. Mm_only:** Những cá nhân chỉ sử dụng tiền di động
  - **3. Mm_plus:** Cá nhân sử dụng tiền di động và cũng sử dụng ít nhất một trong các dịch vụ tài chính khác (tiết kiệm, tín dụng, bảo hiểm)

  ## Phân tích khám phá dữ liệu
  


[datasetLink]: https://zindi.africa/competitions/mobile-money-and-financial-inclusion-in-tanzania-challenge