## Báo cáo Lab 0 (ngắn)
- Em thiết lập môi trường bằng Anaconda với Python 3.10.20 trên Windows 10.
- Sau đó em cài toàn bộ thư viện bằng lệnh pip install -r requirements.txt.
- Em chạy python check_env.py để kiểm tra import, phiên bản thư viện và thiết bị tính toán.
- Kết quả check_env cho thấy các gói chính (NumPy, Pandas, Matplotlib, Scikit-learn, PyYAML, Torch) hoạt động bình thường.
- Torch chạy trên CPU, bài test tensor và linear layer trả về SUCCESS.
- Em tiếp tục chạy python run_smoke_test.py để kiểm tra pipeline huấn luyện tối thiểu.
- Pipeline chạy đủ 3 epoch, test_acc tăng từ 0.52 lên 0.74, không phát sinh lỗi.
- Hệ thống đã sinh đầy đủ file đầu ra gồm checkpoint (smoke_model.pt), biểu đồ loss và log để làm minh chứng.