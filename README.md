# Cisco-Network-Lab

## Mục tiêu
Thực hiện lab Cisco Packet Tracer để:
- Cấu hình, kiểm tra và khắc phục sự cố mạng cơ bản (VLAN, routing, SSH)
- Phân tích lưu lượng và đảm bảo kết nối giữa các thiết bị mạng
- Nâng cao kỹ năng troubleshooting và quản trị mạng

## Công cụ sử dụng
- Cisco Packet Tracer (version 8.x hoặc mới hơn)
- PC/Router/Switch Devices trong Packet Tracer
- Command Line: ping, tracert, show commands, SSH
![Network Diagram](https://github.com/user-attachments/assets/adf2af43-597b-46ef-bafd-b3ce8f567773)

*Hình 1: Diagram mô tả VLAN và Routing giữa các thiết bị*

## Nội dung lab
1. Cấu hình VLAN trên switch
2. Gán IP cho các PC và router
3. Thiết lập routing giữa các VLAN
4. Bật SSH trên router/switch
5. Kiểm tra kết nối bằng ping/tracert
6. Khắc phục lỗi kết nối và phân tích lưu lượng

## File và hình ảnh

### Hình ảnh cấu hình/diagram mạng

![Network Diagram](https://github.com/user-attachments/assets/f63cb965-7c1b-4ea9-a685-151cc3a02ae2)
*ip

### Ping test
![Ping lan10](https://github.com/user-attachments/assets/f63cb965-7c1b-4ea9-a685-151cc3a02ae2)
*Ghi chú: Ping thử LAN 10 và LAN 20*

### Cấu hình IP Route ISP
![IP Route ISP](https://github.com/user-attachments/assets/d32db53c-5529-4522-a4d7-cdf04ec8be54)
*Hình 2: Cấu hình IP Route từ ISP, lưu ý lỗi không ping được ra ngoài mạng*

### Lỗi cấu hình IP tĩnh
![IP Static Error](https://github.com/user-attachments/assets/02c51723-7d51-40c6-999c-d862042b857e)
*Hình 3: Lỗi cấu hình sai IP static, không ping được cùng 1 LAN*
