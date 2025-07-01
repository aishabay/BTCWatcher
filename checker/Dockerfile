FROM python:3.11.9-alpine

WORKDIR /usr/src/app

COPY . .

ENV PYTHONUNBUFFERED 1

RUN pip install --upgrade pip && \
    pip install --no-cache-dir -r requirements.txt

CMD ["python", "app.py"]
