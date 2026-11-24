# Live Translator – Dịch giọng nói trực tiếp

Ứng dụng web miễn phí: đặt điện thoại/laptop cạnh người nói tiếng Trung (Phổ thông), ứng dụng nghe và hiện bản dịch tiếng Anh ngay lập tức. Không cần cài đặt, không cần tài khoản, không có máy chủ riêng.

**Mở ứng dụng:** https://YOUR-USERNAME.github.io/live-translator/

## Cách dùng

1. Mở link trên bằng **Google Chrome** (Android, Windows, Mac) hoặc **Microsoft Edge**. Firefox không hỗ trợ nhận giọng nói.
2. Chọn ngôn ngữ người nói (mặc định: 🇨🇳 Trung Phổ thông) và ngôn ngữ dịch sang (mặc định: English).
3. Bấm **▶ Bắt đầu** và **cho phép dùng micro** khi trình duyệt hỏi.
4. Đặt máy gần người nói. Câu gốc tiếng Trung hiện màu vàng, bản dịch hiện chữ to bên dưới. Chữ in nghiêng mờ là bản tạm, sẽ được chốt lại khi người nói ngắt câu.
5. Bấm **■ Dừng** khi xong.

## Các nút

| Nút | Chức năng |
|---|---|
| A− / A+ | Thu nhỏ / phóng to chữ |
| Hiện gốc | Bật/tắt dòng tiếng Trung gốc |
| 📋 | Sao chép toàn bộ nội dung |
| 🗑 | Xoá màn hình |

## Mẹo & lưu ý

- Cần **kết nối Internet** (nhận giọng nói và dịch đều chạy qua dịch vụ miễn phí của Google).
- Màn hình được giữ sáng khi đang nghe. Nếu chuyển sang ứng dụng khác, việc nghe có thể bị tạm dừng; quay lại trang là tiếp tục.
- Nếu không nghe được: bấm biểu tượng ổ khoá cạnh thanh địa chỉ → cho phép **Micro** → tải lại trang.
- Trên điện thoại Android, Chrome có thể phát tiếng "bíp" mỗi khi phiên nghe tự khởi động lại. Đây là hành vi bình thường của Chrome.
- Bản dịch máy có thể chưa chính xác với tên riêng hoặc thuật ngữ chuyên ngành.
- Âm thanh được gửi tới dịch vụ nhận giọng nói của trình duyệt (Google). Không nên dùng cho nội dung bí mật.

## Chạy thử trên máy

```bash
npx serve live-translator
```

Rồi mở http://localhost:3000 bằng Chrome. Micro chỉ hoạt động trên `localhost` hoặc `https`.
