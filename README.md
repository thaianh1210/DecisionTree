# Decision Tree - Cây quyết định
## Giới thiệu

Cây quyết định (Decision Tree) là một thuật toán học máy phổ biến được sử dụng cho cả bài toán phân loại và hồi quy. Nó được biểu diễn dưới dạng một cây có cấu trúc phân cấp, với mỗi nút thể hiện một quyết định và các nhánh con đại diện cho các kết quả có thể xảy ra. Cây quyết định được xây dựng bằng cách chia tập dữ liệu thành các tập con nhỏ hơn dựa trên các thuộc tính quan trọng nhất, cho đến khi đạt được kết quả mong muốn.

### Ưu điểm:

-Dễ hiểu và diễn giải: Cây quyết định có cấu trúc trực quan, dễ dàng cho con người hiểu và giải thích quy trình ra quyết định.
-Khả năng xử lý dữ liệu đa dạng: Cây quyết định có thể xử lý được nhiều loại dữ liệu khác nhau, bao gồm dữ liệu số, dữ liệu phân loại và dữ liệu văn bản.
-Khả năng chống nhiễu tốt: Cây quyết định ít bị ảnh hưởng bởi nhiễu trong dữ liệu so với các thuật toán học máy khác.
-Không cần chuẩn bị dữ liệu phức tạp: Cây quyết định có thể hoạt động hiệu quả mà không cần chuẩn bị dữ liệu phức tạp.
#### Nhược điểm:

-Dễ bị quá phụ thuộc (overfitting): Cây quyết định có thể dễ dàng bị quá phụ thuộc vào dữ liệu huấn luyện, dẫn đến hiệu suất kém trên dữ liệu mới.
-Khả năng tổng quát hóa thấp: Cây quyết định có thể không tổng quát hóa tốt cho các trường hợp mới, đặc biệt là khi dữ liệu huấn luyện có kích thước nhỏ.
-Độ chính xác có thể bị ảnh hưởng bởi chất lượng dữ liệu: Chất lượng dữ liệu huấn luyện có thể ảnh hưởng đáng kể đến độ chính xác của cây quyết định.
