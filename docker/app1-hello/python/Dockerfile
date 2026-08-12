
From python:3.10-slim
workdir /app
copy requirements.txt requirements.txt
run pip install -r requirements.txt
copy . .
Expose 3000
cmd ["python", "main.py"]