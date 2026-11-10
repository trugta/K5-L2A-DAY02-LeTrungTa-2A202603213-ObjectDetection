# Mini guideline — bài làm cá nhân

> Điền nội dung này trước khi bắt đầu gán nhãn. Giữ lại các quyết định sau khi self-QC.

## Định nghĩa lớp

| Lớp | Định nghĩa của bạn | Ví dụ/điểm phân biệt |
| --- | --- | --- |
| `car` | Là những ô tô thường | xe ô tô thông thường chỉ để chở người thường từ 4 chỗ tới 7 chỗ |
| `truck` | xe tải | xe chở hàng, xe cẩu hoặc xe có thùng phía sau để chở hàng hóa |
| `bus` | xe buýt công cộng | xe lớn dùng để chở người số lượng lớn |
| `van` | xe chở hàng hóa cỡ nhở | khá giống ô tô thường nhưng có thùng hàng ở phía sau dùng để chở đồ |

## Quy tắc chung

- Box bám sát vật thể nghĩa là: box chuẩn
- Vật thể bị che khuất: gán box quanh phần nhìn thấy được nếu nhận diện được lớp.
- Vật thể bị cắt bởi rìa ảnh: Box chạm đúng rìa ảnh khi vật thể bị cắt khung; không đoán phần nằm ngoài ảnh.
- Vật thể rất nhỏ/mơ hồ: không tự đoán. Ghi vào mini guideline và hỏi giảng viên

## Ghi lại quyết định cho ít nhất ba ca mơ hồ

| Ảnh | Tình huống | Quyết định cuối | Lý do theo schema |
| --- | --- | --- | --- |
| `drive_001` | 2 xe chồng lấn lên nhau | chỉ gán nhãn xe ở phía trước | chỉ xe ở phía trước nhận diện được lớp, xe phía sau không nhận diện được |
| `drive_003` | xe bị cắt bởi rìa ảnh | vẫn gán nhãn | vẫn xác định được lớp |
| `drive_016` | xe bị mờ | vẫn gán nhãn | bị mờ những vẫn xác định được lớp |
