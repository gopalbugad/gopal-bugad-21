FROM python:3

WORKDIR /app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY inventory_service /app

EXPOSE 8082

CMD ["python", "inventory_app.py"]
