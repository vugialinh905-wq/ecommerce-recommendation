## Tính năng web

- **Dashboard tổng quan** — biểu đồ phân khúc khách hàng RFM, xu hướng đơn hàng theo tháng, top sản phẩm bán chạy
- **Gợi ý sản phẩm** — nhập mã khách hàng để xem top 5 sản phẩm gợi ý dựa trên lịch sử mua hàng

## Cách chạy

### Yêu cầu
```bash
pip3 install flask pandas --break-system-packages
```

### Chuẩn bị data
Copy các file output vào thư mục `data/`:
data/

├── tong_hop_phan_khuc.csv      

├── xu_huong_theo_thang.csv    

├── top_products.csv           

└── top5_recommendations.csv  

### Chạy server
```bash
python3 app.py
```

### Mở trình duyệt
http://localhost:5000/dashboard     ← Dashboard tổng quan

http://localhost:5000/recommend     ← Gợi ý sản phẩm
