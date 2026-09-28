📓 Nhật ký Prompt
Prompt 1 (Brainstorm – Bước 1)
"Đóng vai chuyên gia JavaScript, hãy liệt kê 5 trường hợp dữ liệu người dùng không đầy đủ có thể làm sập một biểu thức logic đơn giản."

Kết quả nhận được: AI liệt kê các trường hợp như profile = null, name = "", avatar = undefined, role không hợp lệ, status thiếu.
👉 Em dùng để phân tích bảng dữ liệu đầu vào.

Prompt 2 (Phản biện Logic – Bước 2)
"Tôi định dùng toán tử 3 ngôi để hiển thị statusColor theo status. Cách này có tối ưu hơn việc dùng if-else không? Hãy so sánh ưu nhược điểm?"

Kết quả nhận được: AI giải thích toán tử 3 ngôi ngắn gọn hơn, dễ đọc, nhưng nếu lồng nhau quá nhiều sẽ khó bảo trì.
👉 Em quyết định dùng ternary cho statusColor và adminPanel.

Prompt 3 (Pair-programming – Bước 3)
"Giải thích cho tôi tại sao đoạn mã user.name || 'Anonymous' lại chạy nhanh hơn một khối if-else?"

Kết quả nhận được: AI giải thích cơ chế short-circuit của ||, khi vế trái falsy thì trả về vế phải ngay, không cần thêm khối lệnh.
👉 Em áp dụng để viết user?.profile?.name || "Guest".

Prompt 4 (Kiểm thử – Bước 4)
"Hãy đóng vai một người dùng khó tính, cung cấp cho tôi 5 bộ object user dị thường nhất để thử thách tính đúng đắn của toán tử Short-circuit mà tôi vừa viết."

Kết quả nhận được: AI đưa ra các object với null, undefined, NaN, chuỗi rỗng, số 0.
👉 Em dùng để kiểm thử trong HTML.

Prompt 5 (Giải thích cú pháp – Bổ sung)
"forEach((u, i) => { ... }) câu lệnh này nghĩa là sao?"

Kết quả nhận được: AI giải thích u là phần tử, i là chỉ số, và arrow function chạy cho từng phần tử trong mảng.
👉 Em hiểu rõ hơn cách duyệt mảng và in kết quả.
