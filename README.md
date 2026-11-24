# Live Translator – Dịch giọng nói trực tiếp

Ứng dụng web miễn phí: đặt điện thoại/laptop cạnh người nói tiếng Trung (Phổ thông), ứng dụng nghe và hiện bản dịch tiếng Anh ngay lập tức. Không cần cài đặt, không cần tài khoản, không có máy chủ riêng.

**Mở ứng dụng:** https://mycrabs.github.io/live-translator/

## Cách dùng

1. Mở link trên bằng **Google Chrome** (Android, Windows, Mac) hoặc **Microsoft Edge**. Firefox không hỗ trợ nhận giọng nói.
2. Chọn ngôn ngữ người nói (mặc định: 🇨🇳 Trung Phổ thông) và ngôn ngữ dịch sang (mặc định: English).
3. Bấm **▶ Bắt đầu** và **cho phép dùng micro** khi trình duyệt hỏi.
4. Đặt máy gần người nói. Câu gốc tiếng Trung hiện màu vàng, bản dịch hiện chữ to bên dưới. Chữ in nghiêng mờ là bản tạm, sẽ được chốt lại khi người nói ngắt câu.
5. Bấm **■ Dừng** khi xong.

## Dịch video / cuộc gọi đang phát trên máy tính

Khi nghe bằng micro, Chrome tự lọc bỏ âm thanh phát ra từ loa của chính máy đó (chống tiếng vọng), nên video YouTube phát trên cùng máy sẽ không được nhận. Để dịch video hoặc cuộc gọi đang phát trên máy tính:

1. Mở video/cuộc gọi ở một tab Chrome khác.
2. Trong app, chọn **🖥 Âm thanh tab** rồi bấm **▶ Bắt đầu**.
3. Chọn tab đó và bật **"Chia sẻ cả âm thanh của thẻ"** (Share tab audio) → **Chia sẻ**.
4. Muốn dừng: bấm **■ Dừng** hoặc **Dừng chia sẻ** trên thanh của Chrome.

Chỉ có trên **Chrome máy tính** (bản 133 trở lên). Trên điện thoại, tuỳ chọn này tự ẩn đi.

## Các nút

| Nút | Chức năng |
|---|---|
| A− / A+ | Thu nhỏ / phóng to chữ |
| Hiện gốc | Bật/tắt dòng tiếng Trung gốc |
| 📋 | Sao chép toàn bộ nội dung |
| 🗑 | Xoá màn hình |

## Mẹo & lưu ý

- Cần **kết nối Internet** (nhận giọng nói và dịch đều chạy qua dịch vụ miễn phí của Google).
- Người nói liền một mạch không ngắt nghỉ: app tự cắt thành từng câu ngắn (ưu tiên cắt ở dấu câu hoặc trước các từ như 然后, 但是, 所以…) để bản dịch hiện nhanh và dễ đọc.
- Trên Chrome máy tính, app tải thêm **bộ dịch chạy ngay trên máy** (thanh trạng thái hiện "dự phòng trên máy ✓"). Bộ này dùng để hiện bản dịch tạm tức thì, và thay Google khi Google bị lỗi hoặc tạm chặn. Lần đầu có thể mất vài phút để tải.
- Góc phải thanh trạng thái cho biết câu vừa rồi được dịch bằng gì: Google, Chrome (trên máy) hoặc MyMemory.
- Màn hình được giữ sáng khi đang nghe. Nếu chuyển sang ứng dụng khác, việc nghe có thể bị tạm dừng; quay lại trang là tiếp tục.
- Nếu báo **"Lỗi: network"**: hãy mở bằng **Google Chrome**. Edge, Cốc Cốc, Brave, Opera thường không có dịch vụ nhận giọng nói hoạt động. Nếu đã dùng Chrome mà vẫn lỗi, hãy tắt VPN/proxy.
- Nếu không nghe được: bấm biểu tượng ổ khoá cạnh thanh địa chỉ → cho phép **Micro** → tải lại trang.
- Trên điện thoại Android, Chrome có thể phát tiếng "bíp" mỗi khi phiên nghe tự khởi động lại. Đây là hành vi bình thường của Chrome.
- Bản dịch máy có thể chưa chính xác với tên riêng hoặc thuật ngữ chuyên ngành.
- Âm thanh được gửi tới dịch vụ nhận giọng nói của trình duyệt (Google). Không nên dùng cho nội dung bí mật.

## Chạy thử trên máy

```bash
npx serve live-translator
```

Rồi mở http://localhost:3000 bằng Chrome. Micro chỉ hoạt động trên `localhost` hoặc `https`.
