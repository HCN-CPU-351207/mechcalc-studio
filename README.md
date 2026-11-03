# MechCalc Studio – bộ cài và bản cập nhật

Môi trường lập bài tính thiết kế cơ khí theo khối, cho kỹ sư cơ khí (bản PC, Windows).

Kho này **chỉ chứa bộ cài** (không chứa mã nguồn). App MechCalc Studio cài bằng `Setup.exe` tự kiểm tra trang
[Releases](https://github.com/HCN-CPU-351207/mechcalc-studio/releases) khi mở app và mỗi 6 giờ; có bản mới thì tự tải nền,
tải xong báo ở thanh trạng thái để khởi động lại và cập nhật.

## Cài lần đầu

1. Vào [Releases](https://github.com/HCN-CPU-351207/mechcalc-studio/releases), mở bản mới nhất.
2. Tải `MechCalc-Studio-Setup-<phiên bản>.exe` và chạy. Không cần quyền quản trị.
3. Lần đầu Windows có thể hiện cảnh báo SmartScreen (bộ cài chưa ký số): bấm *More info* → *Run anyway*.

## Phát hành bản mới (người quản lý app)

Mỗi bản phát hành gồm đủ 3 tệp: `MechCalc-Studio-Setup-<phiên bản>.exe`, `MechCalc-Studio-Setup-<phiên bản>.exe.blockmap`, `latest.yml`.
Bản ở trạng thái **Draft** (nháp) chưa được phát cho máy nào; bấm **Publish release** thì mọi máy đang dùng bản 0.12.1 trở lên tự nhận.
