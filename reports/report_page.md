# Báo Cáo Thực Hành (Smoke Test)

**1. Thiết lập môi trường:**
Em đã tiến hành tạo môi trường ảo Python và cài đặt các thư viện phụ thuộc từ file `requirements.txt`. Hệ thống đã cài đặt thành công và cấu hình đúng các công cụ cần thiết cho học sâu (như PyTorch).

**2. Các bước kiểm tra đã thực hiện:**
Em đã lần lượt thực thi các kịch bản kiểm tra:
- Chạy lệnh `python check_env.py` để xác minh môi trường hoạt động đúng, PyTorch nhận diện được thiết lập phần cứng.
- Chạy lệnh `python run_smoke_test.py` để kiểm tra khả năng vận hành của toàn bộ luồng huấn luyện (dataloader, mô hình, hàm mất mát).

**3. Vấn đề gặp phải và cách xử lý:**
Quá trình chạy thử nghiệm diễn ra trơn tru mà không gặp phải lỗi nào (exit code 0). Tất cả các tệp kết quả đầu ra mong đợi bao gồm các file log (`env_check.txt`, `smoke_test_log.txt`), biểu đồ (`loss_curve.png`), và trọng số mô hình (`smoke_model.pt`) đều đã được sinh ra đầy đủ và lưu trong thư mục `outputs/` đúng như yêu cầu của bài thực hành.
