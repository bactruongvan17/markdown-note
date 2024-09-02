# Project: Hệ Thống Giám Sát và Cảnh Báo Hiệu Năng Ứng Dụng

## Mô tả

Xây dựng một hệ thống giám sát hiệu năng cho các ứng dụng và dịch vụ web, cho phép theo dõi các thông số quan trọng như CPU, bộ nhớ, lưu lượng mạng, và thời gian phản hồi của ứng dụng. Khi một thông số vượt ngưỡng cho phép, hệ thống sẽ gửi cảnh báo qua email hoặc tin nhắn.

- **Thu thập dữ liệu**: Sử dụng Go để thu thập các thông số hệ thống từ các server và dịch vụ thông qua API hoặc các công cụ giám sát như Prometheus.

- **Phân tích và hiển thị**: Xây dựng một bảng điều khiển (dashboard) đơn giản cho phép người dùng theo dõi các thông số hiệu năng theo thời gian thực.

- **Cảnh báo**: Thiết lập các ngưỡng cảnh báo. Khi một thông số vượt quá ngưỡng đã định, hệ thống sẽ gửi cảnh báo thông qua email, SMS, hoặc các công cụ nhắn tin như Slack.

- **Lưu trữ dữ liệu**: Dữ liệu giám sát sẽ được lưu trữ trong cơ sở dữ liệu như InfluxDB hoặc một giải pháp tương tự để phục vụ cho việc phân tích sau này.

- **Giao diện Web**: Xây dựng giao diện web cho phép người dùng xem và quản lý các cảnh báo, cùng với việc theo dõi hiệu năng.

## Công nghệ sử dụng

- **Go**: Xây dựng các service để thu thập dữ liệu và phân tích.
- **InfluxDB/Prometheus**: Lưu trữ và truy vấn dữ liệu giám sát.
- **Grafana**: Hiển thị dữ liệu giám sát trên dashboard.
- **HTML/CSS/JavaScript**: Xây dựng giao diện quản lý và dashboard.
- **SMTP/Twilio/Slack API**: Gửi cảnh báo qua email hoặc tin nhắn.

## Lợi ích

- Học cách xây dựng hệ thống giám sát với Go.
- Làm quen với việc quản lý và hiển thị dữ liệu hiệu năng của hệ thống.
- Phát triển kỹ năng xử lý và phản ứng với các tình huống khẩn cấp trong vận hành hệ thống.
