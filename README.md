# distance-weighted-knn

Dự án sử dụng thuật toán **k-Nearest Neighbors (k-NN)** để phân loại bộ dữ liệu Iris với việc so sánh hai phương pháp trọng số: **Uniform** và **Distance**.

## 📦 Cài đặt

### Yêu cầu
- Python 3.8+
- pip

### Cài đặt thư viện

```bash
pip install matplotlib seaborn scikit-learn pandas numpy
```

Hoặc chạy trực tiếp trong Jupyter Notebook:

```python
%pip install matplotlib seaborn scikit-learn pandas numpy
```

## 🚀 Sử dụng

1. **Mở file notebook:**
   ```bash
   jupyter notebook FinalML.ipynb
   ```

2. **Chạy các cell theo thứ tự:**
   - **Cell 1:** Import thư viện
   - **Cell 2:** Tải và chuẩn bị dữ liệu (chia 70% train, 30% test)
   - **Cell 3:** Định nghĩa hàm phân tích và vẽ biểu đồ
   - **Cell 4:** Phân tích với trọng số Uniform
   - **Cell 5:** Phân tích với trọng số Distance
   - **Cell 6:** Đánh giá và so sánh kết quả

## Kết quả mong đợi
- Độ chính xác (Accuracy) trên tập test
- Ma trận nhầm lẫn (Confusion Matrix)
- So sánh hiệu suất giữa Uniform và Inverse Distance weights
