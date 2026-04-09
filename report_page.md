# Báo Cáo Thực Hành (Smoke Test)

**1. Thiết lập môi trường:**
Em đã tạo môi trường Python (ảo) và cài đặt các thư viện từ file equirements.txt. Hệ thống nhận diện đúng PyTorch với thiết lập phần cứng.

**2. Các bước kiểm tra đã thực hiện:**
- Chạy lệnh python check_env.py: Mọi thông số hợp lệ.
- Chạy lệnh python run_smoke_test.py: Trơn tru qua các luồng model, dataloader và sinh loss thành công.

**3. Vấn đề gặp phải và cách xử lý:**
Bài thực hành diễn ra suôn sẻ, em không gặp lỗi. Các tệp output (env_check.txt, smoke_test_log.txt, loss_curve.png, smoke_model.pt) đã được sinh đầy đủ lưu tại thư mục outputs/.
