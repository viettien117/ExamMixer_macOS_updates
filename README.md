# ExamMixer cho macOS

**Phần mềm trộn đề thi trắc nghiệm** — đọc ngân hàng câu hỏi từ file Word, tự sinh nhiều mã đề (đảo câu + đảo phương án) và xuất bảng đáp án để chấm bằng [ExamScan](https://github.com/viettien117/ExamScan_Windows_updates).

Repo này host **bản cài đặt macOS** và **kênh cập nhật tự động** cho ExamMixer.

> Dùng Windows? Bản Windows ở [ExamMixer_Windows_updates](https://github.com/viettien117/ExamMixer_Windows_updates).

---

## Tải xuống

1. Vào trang [**Releases**](https://github.com/viettien117/ExamMixer_macOS_updates/releases/latest)
2. Trong mục **Assets**, tải đúng file `.dmg` cho máy của bạn:

| Máy | File |
|---|---|
| Apple Silicon (M1, M2, M3, M4…) | `ExamMixer-x.y.z-osx-arm64.dmg` |
| Intel | `ExamMixer-x.y.z-osx-x64.dmg` |

Không chắc máy mình loại nào? Bấm  → **About This Mac**: dòng **Chip** ghi "Apple M…" là Apple Silicon, ghi "Intel" là Intel.

3. Mở file `.dmg`, kéo **ExamMixer** vào thư mục **Applications**
4. Mở từ Launchpad hoặc thư mục Applications

Ứng dụng **đã được Apple công chứng (notarized)** nên mở được ngay, không hiện cảnh báo "không xác minh được nhà phát triển".

## Yêu cầu hệ thống

- macOS 12 (Monterey) trở lên
- Không cần cài .NET — bản đóng gói đã kèm sẵn

## Cập nhật tự động

Sau khi cài bản đầu tiên, **bạn không cần quay lại trang này nữa**. Ứng dụng tự kiểm tra bản mới khi mở và mỗi 24 giờ, có bản mới thì hỏi bạn rồi tự tải, tự thay thế và tự mở lại.

Kiểm tra thủ công: mở tab **Cập nhật** trong ứng dụng.

> File `.zip` trong mục Assets là **dành cho việc tự cập nhật**, không phải để tải tay. Cài lần đầu thì dùng `.dmg`.

## Bản quyền

Copyright © 2026 RuBi. All rights reserved.
