FROM python:latest
WORKDIR /app
ADD requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY app.py app.py
COPY * /app/*
CMD ["python3", "-u", "/app/app.py"]
