# Quy tắc làm việc nhóm

## Nhánh
- `main` luôn chạy được, không push thẳng.
- Làm việc trên nhánh `feature/<mảng>-<việc>`, ví dụ `feature/rag-ingest`.

## Commit
Dùng tiền tố: `feat:` (tính năng), `fix:` (sửa lỗi), `docs:` (tài liệu), `test:` (kiểm thử), `chore:` (việc khác).
Ví dụ: `feat: thêm tool lấy thời tiết`

## Pull request
1. Mở PR vào `main`, điền đủ mẫu mô tả.
2. Chờ CI (lint, test) báo xanh.
3. Cần ít nhất 1 người rà soát duyệt. Không tự duyệt PR của mình.
4. Giải quyết hết comment rồi mới merge.

## Bí mật
Không đưa khóa API hay dữ liệu khách hàng thật vào repo. Dùng file `.env` (đã được `.gitignore`) và dữ liệu giả lập.
