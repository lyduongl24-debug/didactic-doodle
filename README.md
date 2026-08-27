# didactic-doodle

## Dịch tiếng Trung - Công xưởng

Công cụ web dịch văn bản tự do Việt ⇄ Trung, dùng để dịch tài liệu, thông báo, hướng dẫn trong công xưởng.

### Cách dùng

Mở file `index.html` bằng trình duyệt (double-click, hoặc chạy một server tĩnh bất kỳ, ví dụ `python3 -m http.server`), sau đó:

1. Chọn chiều dịch (中文 → Tiếng Việt hoặc Tiếng Việt → 中文), hoặc bấm "⇄ Đổi chiều".
2. Dán văn bản vào ô bên trái, hoặc tải lên một tệp `.txt`.
3. Bấm "Dịch".
4. Sao chép kết quả hoặc tải về dưới dạng `.txt`.

Không cần cài đặt, không cần API key — chạy hoàn toàn phía trình duyệt, gọi trực tiếp một dịch vụ dịch công cộng miễn phí. Với văn bản dài, công cụ tự động chia nhỏ và dịch theo từng đoạn.

Lưu ý: bản dịch máy chỉ mang tính tham khảo — với tài liệu quan trọng (hợp đồng, quy trình an toàn...), hãy kiểm tra lại bởi người biết cả hai ngôn ngữ.

### Cài đặt lên điện thoại (như một app)

Đây là một Progressive Web App (PWA) — có thể "cài đặt" vào màn hình chính điện thoại như app thật, có icon riêng, chạy toàn màn hình, không cần qua App Store/Google Play.

**Điều kiện:** trang phải được mở qua HTTPS (mở trực tiếp file trên máy sẽ không cài đặt được). Cách đơn giản nhất là bật GitHub Pages cho repo này:

1. Vào repo trên GitHub → **Settings** → **Pages**.
2. Ở mục "Build and deployment", chọn nhánh (branch) muốn deploy (ví dụ `main`) và thư mục `/ (root)`.
3. Lưu lại, đợi vài phút, GitHub sẽ cho một đường link dạng `https://<tên-tài-khoản>.github.io/didactic-doodle/`.

Sau đó trên điện thoại:

- **Android (Chrome):** mở link trên → bấm menu (⋮) → "Thêm vào Màn hình chính" (Add to Home screen).
- **iPhone (Safari):** mở link trên → bấm nút chia sẻ (Share) → "Thêm vào MH chính" (Add to Home Screen).

Sau khi thêm, sẽ có icon riêng trên màn hình chính, mở lên chạy như app (không có thanh địa chỉ trình duyệt). Việc dịch vẫn cần kết nối mạng; phần giao diện app vẫn mở được khi mất mạng.
