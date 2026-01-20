# DAWN_AutoPing

Aidrop : 

Tham Gia Discor ( Vip ) : https://discord.gg/gKxvTNu5

Tham gia NHóm VIp Với Chi Phí 8u/1thang Lợi ích tham gia nhóm ViP Sẽ được cấp keey sử dụng các tool vip trong discor hỗ trợ Và tham khao Code các tool dự án mà các bạn đề xuất

Gửi Phí tháng vào đây và chụp hình gửi trực tiếp cho tôi tại discor để xác nhận Role VIp ☕ https://huynhviet933.github.io/donate_viet_mmo/ Có thể tặng tôi ít cafe tại đây

# HƯỚNG DẪN SỬ DỤNG TOOL DAWN MINER (PHIÊN BẢN LICENSE + AUTO PROXY)

## 1. Yêu cầu hệ thống
- Đã cài đặt NodeJS (phiên bản 16 trở lên).
- Cài đặt các thư viện cần thiết bằng lệnh:
  npm install axios chalk socks-proxy-agent https-proxy-agent

## 2. Chuẩn bị file dữ liệu (Cùng thư mục với tool)
Tool cần 2 file chính để hoạt động:

- **token.json (hoặc token.txt):** 
  + Hỗ trợ định dạng JSON: ["token1", "token2"]
  + Hoặc định dạng text: Mỗi dòng 1 token.
  
- **proxy.txt:** 
  + Định dạng: http://user:pass@ip:port hoặc socks5://user:pass@ip:port
  + Mỗi dòng 1 proxy.
  + ĐẶC BIỆT: Bạn có thể thêm/sửa/xoá proxy trong file này khi tool đang chạy. Tool sẽ tự động cập nhật danh sách mới mỗi khi đổi proxy.

## 3. Cơ chế License (Bản quyền)
- **Lần đầu chạy:** Tool sẽ yêu cầu bạn nhập "License Key".
- **HWID:** Mỗi máy tính có 1 mã HWID riêng biệt. Key phải khớp với HWID của máy mới có thể chạy.
- **Lưu trữ:** Key sau khi nhập sẽ lưu vào file `license.key`. Nếu muốn đổi Key khác, hãy xoá file này.

## 4. Cách vận hành
1. Mở Terminal / Command Prompt tại thư mục chứa tool.
2. Chạy tool bằng lệnh: node fix.js (hoặc tên file bạn đã lưu).
3. Nếu chưa có License, hãy nhập Key khi được yêu cầu.
4. Tool sẽ tự động:
   - Kiểm tra IP qua Proxy.
   - Đăng nhập tài khoản qua Token.
   - Tự động Ping mỗi 20 phút (có random thời gian để tránh bị quét).
   - Tự động đổi Proxy và load lại file `proxy.txt` nếu gặp lỗi kết nối.

## 5. Lưu ý quan trọng
- **Lỗi 401:** Token của bạn đã hết hạn hoặc sai, hãy kiểm tra lại file token.
- **Proxy Die:** Nếu tool báo "Proxy Die", nó sẽ tự động lấy proxy tiếp theo trong danh sách.
- **License Invalid:** Nếu hiện thông báo này, hãy gửi mã HWID hiện lên màn hình cho Admin để được cấp quyền.

---
Chúc bạn cày cuốc hiệu quả!
