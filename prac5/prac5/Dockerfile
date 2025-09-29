FROM python:3.12-slim


WORKDIR /app


COPY . .


RUN pip install --no-cache-dir -r requirements.txt


CMD ["python", "app.py"]
docker build -t [username]/myapp:latest .
docker run -d -p 5050:5000 [username]/myapp:latest