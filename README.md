Code trích xuất số hiệu văn bản luật gốc và các điều luật sửa đổi, bổ sung
Đóng gói bằng FastAPI

Để chạy code, hãy tạo virtual env bằng Python, sau đó activate:
python3 -m venv env
cd env
Scripts\activate

Sau đó cài đặt các thư viện:
pip install -r requirements.txt

Chạy local 
uvicorn app:app --host 0.0.0.0 --port 8000
