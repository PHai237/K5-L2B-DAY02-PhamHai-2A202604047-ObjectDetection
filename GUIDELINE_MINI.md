# Mini guideline — bài làm cá nhân

## Định nghĩa lớp

| Lớp | Định nghĩa của bạn | Ví dụ/điểm phân biệt |
| --- | --- | --- |
| `car` | Ô tô con, SUV, taxi, bán tải | Xe chở người thông thường, không phải bus hay van |
| `truck` | Xe tải, xe ben, đầu kéo | Chủ yếu dùng để chở hàng, có thùng hoặc đầu kéo |
| `bus` | Xe buýt, xe khách | Thân xe thường dài, nhiều cửa sổ, chở nhiều người |
| `van` | Xe van, minivan | Thường nhỏ hơn bus, thân cao, có khoang chở người hoặc hàng |

## Quy tắc chung

- Box bám sát vật thể nghĩa là: Vẽ sát phần xe nhìn thấy, không lấy quá nhiều nền và mỗi xe một box
- Vật thể bị che khuất: Vẫn gán nhãn nếu nhận ra loại xe, không đoán phần bị che
- Vật thể bị cắt bởi rìa ảnh: Chỉ vẽ phần xe trong ảnh, box dừng ở mép
- Vật thể rất nhỏ/mơ hồ: Phóng to để xem, nếu không chắc thì không đoán bừa

## Ghi lại quyết định cho ít nhất ba ca mơ hồ

| Ảnh | Tình huống | Quyết định cuối | Lý do theo schema |
| --- | --- | --- | --- |
| `drive_019` | Hai xe bus ở góc ảnh chồng lên nhau, dễ tưởng là box trùng | Giữ cả hai box bus | Có hai xe riêng biệt nên mỗi xe cần một box |
| `drive_040` | Nhiều xe đứng sát nhau, một số bị che gần hết thân xe | Vẽ riêng từng xe còn nhận diện được | Không gộp các xe vào một box, chỉ lấy phần nhìn thấy |
| `drive_050` | Xe bus lớn bị cắt một phần ở mép dưới ảnh | Giữ nhãn bus, box dừng ở mép ảnh | Xe vẫn nhận diện được, không cần đoán phần nằm ngoài ảnh |
