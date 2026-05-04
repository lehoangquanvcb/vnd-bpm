# VNDIRECT BPM

## Chạy local
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Deploy
Đưa toàn bộ thư mục lên GitHub, sau đó deploy trên Streamlit Cloud với entry file `app.py`.

## Dữ liệu
Mặc định dùng CSV demo để chạy ổn định. Có thể thay bằng dữ liệu thật hoặc mở rộng connector trong `modules/market_data_connector.py`.
