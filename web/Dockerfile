FROM python:3.9-alpine

WORKDIR /app

RUN pip install kubernetes requests flask uuid

COPY . .

EXPOSE 5000

CMD ["python3", "app.py"]