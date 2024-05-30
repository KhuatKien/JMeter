# JMeter
# Mục tiêu:
- Sử dụng jMeter để tạo một kịch bản kiểm tra mô phỏng người dùng truy cập trang web https://www.youtube.com/

- Chạy kịch bản kiểm tra và ghi lại kết quả.
- Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.
- Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của trang web.

#Kịch bản kiểm tra:

- Thread Group:
Số lượng thread: 100
Thời gian chạy: 100 giây
Ramp-up period: 10 giây
- HTTP Request: URL: https://www.youtube.com/
- Method: GET
- Content encoding: UTF-8
# Listeners:
- View Results Tree
- Aggregate Report

# Kết quả kiểm tra:

![image](https://github.com/KhuatKien/JMeter/assets/91423106/9985e17b-1a39-4a72-bf37-eab7e741b3f9)

![image](https://github.com/KhuatKien/JMeter/assets/91423106/a1432395-c2ff-450a-8788-babef9478afa)
