# CNTT1-nh-p-m-n-c-ng-ngh-th-ng-tin-Session15_Ex04
### 1. Giải pháp Kỹ thuật

**Tối ưu Files On-Demand & Băng thông:**

* **Bật Files On-Demand:** Vào **OneDrive Settings** > **Sync and backup** > **Advanced settings** > Bật **Files On-Demand**.
* **Trạng thái lưu trữ:**
* Icon đám mây: File chỉ nằm trên Cloud (0 MB ổ cứng).
* Icon tích xanh viền trắng: File tải về tạm thời khi mở.
* Click chuột phải vào file/thư mục chọn **Free up space** để xóa dữ liệu lưu tạm trên SSD, trả file về Cloud.


* **Cấu hình dọn dẹp tự động:** Mở **Windows Settings** > **System** > **Storage** > Bật **Storage Sense** và hẹn lịch giải phóng file sau 7–14 ngày không dùng.
* **Xử lý bẫy đường truyền & đứt kết nối:**
* Vào **OneDrive Settings** > **Network**: Giới hạn tốc độ Upload ở mức 50–70% băng thông mạng trọ.
* Vào **Windows Power Options**: Chỉnh mục *"When I close the lid"* thành **Do nothing** (khi cắm sạc) để treo máy upload đêm mà không ngắt mạng.



---

## 2. Báo cáo & Phân tích Dung lượng

* **Bài toán:** 500 GB video > 180 GB SSD khả dụng (256 GB trừ 76 GB hệ điều hành/phần mềm). Tràn ổ cứng ngay nếu sync thông thường.
* **Hiệu quả thực tế:**
* **Dung lượng hiển thị trên máy:** 500 GB (đầy đủ cây thư mục để tìm kiếm, làm việc).
* **Dung lượng thực tế chiếm SSD:** **~0 GB** (toàn bộ ở dạng Online-only).
* **Tải file linh hoạt:** Chỉ tải đúng video cần dựng/xem, xử lý xong nhấn **Free up space** để hạ dung lượng về 0.



---

## 3. Quy trình Vòng đời Dữ liệu

1. **Upload:** Chép video từ thẻ nhớ vào thư mục sync -> Cloud tự tải lên -> Click chuột phải chọn **Free up space**.
2. **Sử dụng:** Double-click file video cần làm việc để máy tự tải về tạm thời.
3. **Lưu trữ:** Storage Sense tự trả file về trạng thái Online-only sau 7 ngày không dùng.
