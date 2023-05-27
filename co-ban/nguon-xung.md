# Nguồn xung (SWITCHING)

## Mỗi khối nguồn gồm các thành phần cơ bản
    Khối giao động tạo xung
    Khối công suất
    Khối hồi tiếp áp DC so sánh điều khiển độ rộng xung ra nhằm ổn định điện thế
    Khối hồi tiếp xung để ổn định tần số giao động
Riêng phần nguồn sạc và một số phần nguồn khác có thêm khối hồi tiếp nhận dạng dòng để phục vụ cho bảo vệ chạm tải hoặc cắt dòng sạc khi pin đầy

## Điều kiện cơ bản của khối nguồn xung
    IC nguồn phải được cấp nguồn DC
    Một đường điện áp quyết định tần số làm việc của khối giao động, tuỳ theo thiết kế của mỗi loại IC mà ta có thể cấp áp vào để có xung vuông dao động ở tần số khác nhau vd như cấp 0v thì ta có dao động 200KHz, 2v: 300KHz, 3,3v: 400KHz v.v..
    Một đường mở/tắt, là đường nhận lệnh từ nơi khác vd từ IC IO, hoặc từ chíp nam, v.v.. sẽ cho phép xung vuông thoát ra khỏi IC cấp vào cực G của cặp FET điều khiển nguồn ra
    Đường hồi tiếp xung dùng để duy trì tần số dao động luôn đúng theo thiết kế
    Đường hồi tiếp áp dùng ổn định điện áp luôn đúng trong khoảng 1/300.000s
Một số khối nguồn có thêm khối nhận dạng dòng tải