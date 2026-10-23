# tiktok_post — hàng chờ đăng

Trang tĩnh phục vụ việc đăng bài TikTok thủ công từ điện thoại.
GitHub Pages: **https://dzodzanh.github.io/tiktok_post/**

- `index.html` — trang hàng chờ (App → Tài khoản → Ngày; lưu ảnh, copy title/caption).
- `queue.json` — dữ liệu bài, sinh bởi `scripts/build_queue.py` trong project `tiktok_automation`.
- `media/<ngày>/<app>/<format>/<NN>/<k>.jpg` — slide 1080 px.

Cập nhật: trong project chạy `.venv/bin/python -m scripts.build_queue <YYYY-MM-DD> …`
— script ghi vào thư mục này rồi tự commit và push.
