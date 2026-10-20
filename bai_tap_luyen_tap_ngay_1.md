
# Đào Tuấn Minh
## Bài tập luyện tập ngày 1
### Phần 3
>sử dụng Windows PowerShell
    Pwd
    Kết quả:
    D:\Project_CNTT\testNMCNTT\trung-tam-tieng-anh
---
    ls -Force
    Kết quả:
    Directory: D:\Project_CNTT\testNMCNTT\trung-tam-tieng-anh
    Mode LastWriteTime Length Name
    d----- 10/20/2026 8:30 PM archive
    d----- 10/20/2026 8:33 PM data
    d----- 10/20/2026 8:30 PM docs
    d----- 10/20/2026 8:33 PM logs
    d----- 10/20/2026 8:30 PM media
    d----- 10/20/2026 8:35 PM Trung Tam Tieng Anh FINAL
    d------ 10/19/2026 10:04 AM 902 bai_lam_ngay1.md

---
    ``Power Shell 
    mv '.\Trung Tam Tieng Anh FINAL\lich_hoc.txt' ".\docs"
    mv ".\Trung Tam Tieng Anh FINAL\anh_lop_hoc.JPG" ".\media"
    mv ".\Trung Tam Tieng Anh FINAL\logo_trung_tam.PNG" ".\media"
---
    ``Power Shell
    cp ".\media\logo_trung_tam.PNG" ".\archive\"
---
    ``Power Shell
    rm ".\Trung Tam Tieng Anh FINAL\temp_201.tmp"
    rm ".\Trung Tam Tieng Anh FINAL\temp_202.tmp"
---
    ``Power Shell
    cd ".\logs"
    ls
    cd..
 ---
    ``Power Shell
    Get-ChildItem -r -force
