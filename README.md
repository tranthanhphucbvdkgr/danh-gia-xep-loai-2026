# Ứng dụng đánh giá, xếp loại chất lượng viên chức năm 2026

Trung tâm Y tế Giồng Riềng · Trần Thanh Phúc

**Truy cập:** https://tranthanhphucbvdkgr.github.io/danh-gia-xep-loai-2026/

Căn cứ Nghị định 233/2026/NĐ-CP, Công văn 5912/UBND-TH, Công văn 9400/SYT-TCCB.

## Đăng nhập
- Chỉ tài khoản do quản trị viên cấp và phê duyệt mới đăng nhập được. Liên hệ Trần Thanh Phúc để được cấp tài khoản.
- Danh sách tài khoản lưu trong file `accounts.json` của repo này. Chỉ chủ repo (người có quyền ghi) mới thêm, khóa hoặc xóa được tài khoản.
- Dữ liệu nhân sự và biểu mẫu trong `index.html` được mã hóa AES-256-GCM. Không lưu mật khẩu; mỗi tài khoản chỉ lưu khóa đã bọc (PBKDF2-SHA256, 310.000 vòng).
- Cần kết nối Internet khi đăng nhập.

## Chức năng
- 3 tab đánh giá: Lãnh đạo, quản lý (Phụ lục 3) · Viên chức (Phụ lục 2) · Tập thể khoa, phòng (Phụ lục 1).
- Tự chấm điểm 6 tháng, Quý IV, điểm năm = (6 tháng × 2 + Quý III + Quý IV) : 4 và mức xếp loại.
- Xuất file Word đúng mẫu A1–A6, B1–B6, C1–C3 và Excel D1, E1, E2.
- Tab "Quản trị tài khoản" (chỉ quản trị viên): cấp, sửa, đặt lại mật khẩu, khóa, xóa tài khoản và lưu thẳng lên GitHub.

## Lưu ý
- Dữ liệu nhập lưu trong trình duyệt của từng người dùng; dùng "Sao lưu dữ liệu" để chuyển máy.
