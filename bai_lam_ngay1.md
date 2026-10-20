# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:** Nguyễn Vũ Long
- **Lớp:** HN-KS26-CNTT3
- **Link repository:**[GitHub](https://github.com/vulong1712/CNTT3_Nhap-mon-CNTT_OnTap-Ngay1)
- **Hệ điều hành (Windows/macOS):** Windows

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.


## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

B1
```powershell
pwd
```
B2
```powershell
ls -Force
```
B3
```powershell
mv .\Lich_Hoc.txt .\docs\
mv .\Anh_Lop_Hoc.JPG .\media\
mv .\Logo_Trung_Tam.PNG .\media\
```
B4
```powershell
cp .\media\Logo_Trung_Tam.PNG .\archive\
```
B5
```powershell
rm -r .\temp_201.tmp
rm -r .\temp_202.tmp
```
B6
```powershell
cd .\logs\
ls
cd ..
```
B7
```powershell
cd docs
cp ..\media\Anh_Lop_Hoc.JPG ..\archive\
cd ..
```
B8
```powershell
Get-ChildItem -Recurse -Force
```

### Kết quả B1 (pwd)
```text
Path
---
D:\starter-kit\starter-kit\Trung Tam Tieng Anh FINAL

```
B2
```text
 Directory: D:\starter-kit\starter-kit\Trung Tam Tieng Anh FINAL
Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        19/10/2026  10:04 AM             83 .env
-a----        19/10/2026  10:04 AM           1072 Access.log
-a----        19/10/2026  10:04 AM          13559 Anh Lop Hoc.JPG
-a----        19/10/2026  10:04 AM           5070 Hoc Vien Khoa 3.xlsx
-a----        19/10/2026  10:04 AM             67 Lich Hoc.txt
-a----        19/10/2026  10:04 AM           5184 Logo Trung Tam.PNG
-a----        19/10/2026  10:04 AM             22 temp_201.tmp
-a----        19/10/2026  10:04 AM             22 temp_202.tmp
```
B3
```text
(Không có output)
```

B4
```text
(Không có output)
```

B5
```text
(Không có output)
```
B6
```text
Directory: D:\starter-kit\starter-kit\Trung Tam Tieng Anh FINAL\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        19/10/2026  10:10 AM           1072 Access.log
```
B7
```text
(Không có output)
```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
Directory: D:\starter-kit\starter-kit\Trung Tam Tieng Anh FINAL
Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        19/10/2026   9:20 PM                archive
d-----        19/10/2026   9:11 PM                data
d-----        19/10/2026   9:18 PM                docs
d-----        19/10/2026   9:12 PM                logs
d-----        19/10/2026   9:20 PM                media
-a----        19/10/2026  10:04 AM             83 .env
```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** 100/100
- **Lỗi mình đã mắc và cách sửa:** Không có điểm yếu
