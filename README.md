# bt1SS1_IT103B

1. Phân tích lỗi

rawFoodPrice, rawToppingPrice và rawDeliveryFee là kiểu String nên toán tử + thực hiện nối chuỗi thay vì cộng số.

Ví dụ:

"55000" + "15000" → "5500015000"

Sử dụng Number() để ép kiểu sang số trước khi tính toán.

2. Test Cases
Trường hợp	Kết quả sai	Kết quả đúng
Tổng tiền món ăn	5500015000 VND	70000 VND
Tổng thanh toán	550001500020000 VND	80000 VND
3. Kết quả
Tổng tiền món ăn: 70000 VND
Số tiền thanh toán thực tế: 80000 VND

Kiểm thử bằng cách mở index.html trên trình duyệt → nhấn F12 → chọn Console.
