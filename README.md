# 2weet Map 🍰

Web app tra cứu & khám phá các tiệm bánh tại TP. Hồ Chí Minh — lọc theo khu vực, hình thức (cửa hàng/online/hybrid), dòng bánh, chế độ ăn, và lưu tiệm yêu thích.

## Tính năng
- Tìm kiếm & lọc tiệm bánh theo quận, hình thức, dòng bánh, chế độ ăn (vegan, gluten-free, ...)
- Sắp xếp theo khoảng cách từ vị trí hiện tại hoặc khu vực đã chọn
- Lưu tiệm yêu thích, đồng bộ real-time qua Firebase (dùng chung mọi thiết bị/trình duyệt)
- Đề xuất tiệm mới kèm ảnh, chờ duyệt
- Chỉ đường nhanh qua Google Maps / Apple Maps / Grab

## Công nghệ
- HTML/CSS/JS thuần (không dùng framework)
- [Firebase Realtime Database](https://firebase.google.com/products/realtime-database) để đồng bộ dữ liệu tiệm bánh và danh sách yêu thích

## Chạy thử
Mở trực tiếp `index.html` bằng trình duyệt, hoặc deploy qua GitHub Pages / bất kỳ static hosting nào.

## Cấu hình Firebase
Project này dùng chung 1 Firebase config cho cả trang khách (`index.html`) và trang quản lý duyệt tiệm. Nếu bạn fork repo này, nhớ thay `firebaseConfig` trong file bằng project Firebase của riêng bạn để tránh ghi đè dữ liệu.

## Ghi chú
Dự án cá nhân, đang trong giai đoạn hoàn thiện — có thể còn thay đổi cấu trúc/tính năng.
