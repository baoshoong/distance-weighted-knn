# distance-weighted-knn

Triển khai bộ phân loại k-NN (k-Nearest Neighbors), một phương pháp học lười (lazy learning). So sánh hiệu suất phân loại khi sử dụng hai phương pháp trọng số khác nhau:
- **Uniform**: Trọng số bằng nhau cho tất cả hàng xóm
- **Inverse Distance**: Trọng số nghịch đảo khoảng cách (hàng xóm gần có ảnh hưởng lớn hơn)

Dự án sử dụng tập dữ liệu **Iris** (150 mẫu, 4 đặc trưng, 3 lớp hoa) để đánh giá và so sánh hiệu suất của hai phương pháp.

## Cài đặt
```bash
pip install -r requirements.txt
```

## Sử dụng
```bash
python compare_weights.py
```

## Kết quả mong đợi
- Độ chính xác (Accuracy) trên tập test
- Ma trận nhầm lẫn (Confusion Matrix)
- So sánh hiệu suất giữa Uniform và Inverse Distance weights