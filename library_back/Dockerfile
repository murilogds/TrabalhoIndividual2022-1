# Dockerfile

FROM python:3.8

COPY requirements.txt requirements.txt
RUN echo "nameserver 8.8.8.8" > /etc/resolv.conf
RUN pip install --no-cache-dir -r requirements.txt

COPY . app
WORKDIR /app

EXPOSE 8000