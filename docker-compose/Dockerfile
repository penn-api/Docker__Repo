FROM python:3.12-slim

WORKDIR /app

COPY requirement_flask.txt .
RUN pip install --no-cache-dir -r requirement_flask.txt

COPY . .


EXPOSE 5000
CMD ["python", "app.py"]
