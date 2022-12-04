# Images Products Recommendation System with CNN

Hầu hết các công cụ tìm kiếm mua sắm
trực tuyến vẫn chủ yếu phụ thuộc vào nền tảng kiến thức và
sử dụng đối sánh từ khóa làm chiến lược tìm kiếm của họ để
tìm sản phẩm có khả năng mà người tiêu dùng muốn mua nhất.
Điều này không hiệu quả theo cách mô tả sản phẩm có thể khác
nhau rất nhiều từ phía người bán sang phía người mua.
Trong bài báo này, chúng tôi trình bày một công cụ tìm kiếm
thông minh để mua sắm trực tuyến.Về cơ bản, chúng tôi sử dụng
hình ảnh làm đầu vào và cố gắng để hiểu thông tin về sản phẩm
từ những hình ảnh này. Đầu tiên, chúng tôi sử dụng mạng nơ-ron để phân loại hình ảnh đầu vào là một trong các danh mục
sản phẩm. Sau đó, sử dụng một mạng nơ-ron khác để lập mô
hình điểm giống nhau giữa các cặp hình ảnh, mà chúng được
sử dụng để chọn sản phẩm gần nhất trong bộ dữ liệu sản phẩm
của chúng tô. Chúng tôi sử dụng Jaccard similarity để tính toán
điểm giống nhau cho quá trình đào tạo dữ liệu. Chúng tôi thu
thập dữ liệu thông tin sản phẩm (bao gồm hình ảnh, nhãn lớp,
giá, tên sản phẩm, ...) từ Amazon để tìm hiểu các mô hình này.
Cụ thể, tập dữ liệu của chúng tôi chứa thông tin về 9,2 triệu sản
phẩm có hình ảnh và có tổng cộng có hơn 20 danh mục. Phương
pháp của chúng tôi đạt được độ chính xác phân loại là 0.48.
Cuối cùng, chúng tôi có thể giới thiệu các sản phẩm có mức độ
tương tự cao hơn 0,48 và cung cấp hỗ trợ mua sắm trực tuyến
nhanh chóng và chính xác.
