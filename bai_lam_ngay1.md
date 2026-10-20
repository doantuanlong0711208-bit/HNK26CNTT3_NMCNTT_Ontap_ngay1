# Đoàn Tuấn Long
## Bài tập luyện ngày 1
### Các câu lệnh được em sử dụng trên Windows PowerShell
 B1:
 ```Powershell
 1. pwd
 2. kết quả:
 3. ----
D:\starter-kit\trung-tam-tieng-anh
```
B2:
```Powershell
1. ls -Force
2. kết quả:
3. Directory: D:\starter-kit\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
------        10/19/2026  10:04 AM             83 .env
-a----        10/19/2026  10:04 AM          13559 anh_lop_hoc.jpg
-a----        10/19/2026  10:04 AM            902 bai_lam_ngay1.md
-a----        10/19/2026  10:04 AM             67 lich_hoc.txt
-a----        10/19/2026  10:04 AM           5184 logo_trung_tam.png
------        10/19/2026  10:04 AM             22 temp_201.tmp
------        10/19/2026  10:04 AM             22 temp_202.tmp
```
B3
```Powershell
mv lich_hoc.txt docs/
mv logo_trung_tam.png media/
mv anh_lop_hoc.jpg media/
```
B4
```Powershell
cp media/logo_trung_tam.png archive/
```
B5
```Powershell
rm ".\temp_201.tmp\"
rm ".\temp_202.tmp\"
```
B6
```Powershell
cd ..
cd ".\logs\"
ls
cd ..
```
B7
```Powershell
cd docs
cp "..\media\anh_lop_hoc.JPG" "..\archive\"
cd ..
```
B8
```Powershell
Get-ChildItem -r -force
```
 
