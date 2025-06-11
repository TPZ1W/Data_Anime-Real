# 🎌 Anime Data Visualization Project

![Login Interface]()

## 📌 Giới thiệu
Đây là đồ án cuối kỳ môn Python. Dự án cung cấp một ứng dụng giao diện người dùng (GUI) giúp:
- Quản lý dữ liệu Anime từ file CSV
- Làm sạch, trực quan hóa, chuẩn hóa dữ liệu
- Hỗ trợ tìm kiếm và thao tác CRUD
- Tích hợp tìm kiếm video anime trên YouTube
- Tạo bộ sưu tập yêu thích

---

## 🚀 Tính năng nổi bật

| Tính năng                          | Mô tả |
|-----------------------------------|-------|
| 🔍 Tìm kiếm                       | Tìm kiếm theo tên, mô tả, tag, thể loại |
| 📊 Trực quan hóa dữ liệu         | Boxplot, Heatmap, Phân bố tập phim, Top 10 |
| 🧹 Làm sạch và chuẩn hóa dữ liệu | Xử lý giá trị null và scale dữ liệu |
| 📝 CRUD đầy đủ                   | Thêm, sửa, xóa, làm mới dữ liệu |
| 📺 YouTube Search                | Tìm video liên quan đến anime |
| 🗂️ Bộ sưu tập                    | Lưu trữ các anime yêu thích riêng |
| 📁 Chọn file CSV khác            | Hỗ trợ tùy chọn file dữ liệu ngoài |





## 🛠️ Công nghệ sử dụng

- Python 3.x
- Tkinter (GUI)
- Pandas, NumPy
- Seaborn, Matplotlib
- `tksheet`, `youtubesearchpython`

---

## 🗂️ Cấu trúc thư mục

```
├── main.py
├── login_gui.py
├── collection_gui.py
├── service/
│   ├── csv_helper.py
│   ├── chart_service.py
│   ├── collection_service.py
│   ├── data_clean_service.py
│   └── standard_scaler_service.py
├── data/
│   ├── Anime.csv
│   └── about_project.txt
├── assets/
│   ├── login_interface.png
│   ├── main_gui.png
│   ├── outlier_chart.png
│   ├── heatmap_chart.png
│   └── scaled_chart.png
```

---

## ⚙️ Cài đặt và chạy

```bash
# Bước 1: Cài thư viện
pip install -r requirements.txt

# Bước 2: Chạy ứng dụng
python main.py
```

  
