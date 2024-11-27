# Mạch Mtiny Programmer (Arduino Compatible)

![](/image/mtiny_Prg_01.jpg)

## Giới thiệu

Mạch Mtiny Programmer (Arduino Compatible) được nghiên cứu và và sản xuất bởi MakerLab.vn mà một mạch chuyển USB-UART được thiết kế chuyên dụng để nạp chương trình và giao tiếp máy tính cho các mạch trong Series Mtiny sử dụng chuẩn nạp Mtiny Socket - IDC 8-Pin (2x4), mạch tương thích với phần mềm Arduino và có thể sử dụng với hầu hết các hệ điều hành phổ biến hiện nay: Windows, MacOS, Linux,...

> Mtiny là viết tắt của Maker Tiny là dự án tạo ra các mạch vi điều khiển với thiết kế nhỏ gọn sử dụng chuẩn chân cắm DIP 2.54mm, các mạch Mtiny cùng sử dụng chung mạch nạp chương trình và giao tiếp máy tính Mtiny Programmer với chuẩn nạp Mtiny Socket.

Các mạch Mtiny hỗ trợ nạp chương trình và giao tiếp máy tính bằng mạch Mtiny Programmer:

- Mạch Mtiny Uno ATmega328P (Arduino Compatible)
- Mạch Mtiny ESP8266 ESP-07S (Arduino Compatible)
- Mạch Mtiny ESP8266 ESP-12S (Arduino Compatible)
- Mạch Mtiny ESP32 WROOM-32E (Arduino Compatible)
- Mạch Mtiny ESP32 WROOM-32UE (Arduino Compatible)
- Mạch Mtiny ESP32 WROVER-IE (Arduino Compatible)

## Thông số kỹ thuật

Model Mạch Mtiny Programmer (Arduino Compatible)
Main IC USB-UART CH340
Power Supply 5VDC USB-C
Interface UART
5VDC Output Current Max 500mA
3.3VDC Output Current Max 700mA
Pinout 5V, 3V3, GND, TX, RX, IO0, AR (Arduino Reset), ER (ESP Reset)
Compatible Mtiny Series
Programmer Connector Mtiny Socket - IDC 8-Pin (2x4)

## Các chân tín hiệu

![](/image/mtiny_Prg_02.png)

AR (Arduino Reset) Chân phát tín hiệu Reset cho các mạch thuộc hệ Arduino
3V3 Chân cấp nguồn 3.3VDC tối đa 700mA
5V Chân cấp nguồn 5VDC tối đa 500mA
GND Chân cấp nguồn GND 0VDC
IO0 Chân kết nối với IO0 của ESP để kích hoạt nạp chương trình
ER (ESP Reset) Chân cấp tín hiệu Reset / EN cho các mạch ESP
TX Chân truyền tín hiệu UART của CH340 (tương thích 3.3/5VDC)
RX Chân nhận tín hiệu UART của CH340 (tương thích 3.3/5VDC)

## Kích thước

![](/image/mtiny_Prg_03.jpg)

## Hình ảnh

![](/image/mtiny_Prg_04.jpg)

## Hướng dẫn sử dụng

1) Cài đặt Driver:

> Lưu ý:
Mạch Mtiny Programmer sử dụng chip nạp CH340 nên việc cài đặt Driver sẽ theo Hướng dẫn cài đặt Driver cho các mạch sử dụng IC giao tiếp USB-UART CH34x.

2) Hướng dẫn kết nối Mtiny Programmer với các mạch Mtiny để nạp chương trình và giao tiếp máy tính:
Các mạch Mtiny đều sử dụng chung chuẩn nạp chương trình và giao tiếp máy tính Mtiny Socket để kết nối với mạch Mtiny Programmer như hình dưới đây:

![](/image/mtiny_Prg_05.jpg)

Để có độ tuỳ biến cao các mạch Mtiny có thể đã được hàn rào kết nối sẵn hoặc chưa hàn, nếu chưa hàn các bạn có thể hàn Mtiny Socket sử dụng rào đực đôi Header 2x4pins theo chiều hướng lên và kết nối như sau:

![](/image/mtiny_Prg_06.jpg)

Sau khi đã hàn rào các bạn kết nối các mạch Mtiny với Mạch Mtiny Programmer bằng cáp IDC 2x4pins, kết nối Mạch Mtiny Programmer với máy tính bằng cáp USB-C sẽ thấy Led nguồn PWR trên mạch Mtiny Programmer và Mtiny phát sáng, kiểm tra máy tính đã nhận Driver của mạch Mtiny Programmer như ở bước 1 là đã có thể sử dụng:

![](/image/mtiny_Prg_07.jpg)

## Nhà phân phối

Có thể mua Mạch Mtiny Programmer (Arduino Compatible) tại các nhà phân phối sau:

- [Hshop.vn - Điện tử & Robot.](hshop.vn)
