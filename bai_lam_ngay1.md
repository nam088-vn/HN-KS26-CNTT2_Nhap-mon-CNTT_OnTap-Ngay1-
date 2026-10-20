# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:** Nguyễn Thành Nam
- **Lớp:**CNTT2
- **Link repository:**
- **Hệ điều hành (Windows/macOS):** macOS

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy 
ls -a
mv lich_hoc.txt docs/
mv logo_trung_tam.png media/
mv anh_lop_hoc.jpg media/
cp media/logo_trung_tam.png archive/
rm temp_201.tmp
rm temp_202.tmp
cd logs
ls -a
cd ..
cd docs
cp ../media/anh_lop_hoc.jpg ../archive/
cd ..
### Kết quả B1 
thanhnam@mac-cua-a-namm trung-tam-tieng-anh

### Kết quả liệt kê toàn bộ dự án 
.:
.                   .env                docs/
..                  archive/            logs/
.DS_Store           bai_lam_ngay1.md    media/
.localized          data/

./archive:
.                  ..                 anh_lop_hoc.jpg    logo_trung_tam.png

./data:
.                    ..                   hoc_vien_khoa_3.xlsx

./docs:
.            ..           lich_hoc.txt

./logs:
.          ..         access.log

./media:
.                  ..                 anh_lop_hoc.jpg    logo_trung_tam.png
## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
