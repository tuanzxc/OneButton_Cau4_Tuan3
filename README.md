# Dự án điều khiển LED bằng nút nhấn sử dụng thư viện OneButton.
By Nguyễn Viết Tuấn

## Các chức năng chính
Sử dụng một nút bấm để điều khiển đèn LED theo 3 trạng thái khác nhau:
* Single click: bật/tắt đèn.
* Double click: đèn nhấp nháy.

## Phần cứng
1. ESP32 Devkit v1:
* Con chip ESP32 kiến trúc xtensa, lõi kép.
* Tích hợp Blue LED vào chân GPIO02, active level = HIGH.
* Tích hợp nút bấm (BOOT) vào chân GPIO00, active level = LOW.

## Hướng dẫn sử dụng
B1: Tải file dự án về
B2: Sử dụng PlatformIO để mở Project này.

