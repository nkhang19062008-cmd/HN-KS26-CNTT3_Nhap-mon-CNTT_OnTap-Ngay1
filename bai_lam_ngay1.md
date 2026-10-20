# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:Nguyễn Trường Khang**
- **Lớp:HN-KS26-CNTT3**
- **Link repository:https://github.com/nkhang19062008-cmd/HN-KS26-CNTT3_Nhap-mon-CNTT_OnTap-Ngay1**
- **Hệ điều hành (Windows/macOS):Windows**

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)
```shell
pwd
ls -Force
mv lich_hoc.txt docs/
mv logo_trung_tam.png media/
mv anh_lop_hoc.jpg media/
cp media/logo_trung_tam.png archive/
rm temp_201.tmp
rm temp_202.tmp
cd logs; ls; cd ..
cd docs; cp ../media/anh_lop_hoc.jpg ../archive/; cd ..

### Kết quả B1 (pwd)

```
Plaintext
D:\bai 20 thang 10\starter-kit\starter-kit\trung-tam-tieng-anh

```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```Plaintext
    Directory: D:\bai 20 thang 10\starter-kit\starter-kit\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026   8:28 PM                archive
d-----        10/20/2026   8:06 PM                data
d-----        10/20/2026   8:17 PM                docs
d-r---        10/20/2026   7:52 PM                Documents
d-----        10/20/2026   8:06 PM                logs
d-----        10/20/2026   8:17 PM                media
------        10/19/2026  10:04 AM             83 .env


    Directory: D:\bai 20 thang 10\starter-kit\starter-kit\trung-tam-tieng-anh\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM          13559 anh_lop_hoc.jpg
-a----        10/19/2026  10:04 AM           5184 logo_trung_tam.png


    Directory: D:\bai 20 thang 10\starter-kit\starter-kit\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM           5070 hoc_vien_khoa_3.xlsx


    Directory: D:\bai 20 thang 10\starter-kit\starter-kit\trung-tam-tieng-anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM             67 lich_hoc.txt


    Directory: D:\bai 20 thang 10\starter-kit\starter-kit\trung-tam-tieng-anh\Documents


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         10/1/2026   2:48 PM                Custom Office Templates
d-----        10/20/2026   7:52 PM                League of Legends
d-----        10/20/2026   7:52 PM                WindowsPowerShell
-a----        10/14/2026   4:20 AM          15528 CNTT3_NMCNTT_Session07_Ex07.docx
-a----        10/15/2026   3:40 AM          16770 CNTT_NMCNTTSession08_Ex04.docx
-a-hs-         9/23/2026  10:43 AM            402 desktop.ini


    Directory: D:\bai 20 thang 10\starter-kit\starter-kit\trung-tam-tieng-anh\Documents\League of Legends


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         9/23/2026   2:38 AM                Replays


    Directory: D:\bai 20 thang 10\starter-kit\starter-kit\trung-tam-tieng-anh\Documents\WindowsPowerShell


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/13/2026   3:05 PM             68 Microsoft.PowerShell_profile.ps1


    Directory: D:\bai 20 thang 10\starter-kit\starter-kit\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM           1072 access.log


    Directory: D:\bai 20 thang 10\starter-kit\starter-kit\trung-tam-tieng-anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM          13559 anh_lop_hoc.jpg
-a----        10/19/2026  10:04 AM           5184 logo_trung_tam.png


PS D:\bai 20 thang 10\starter-kit\starter-kit\trung-tam-tieng-anh>
```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
