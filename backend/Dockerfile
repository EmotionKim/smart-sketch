FROM python:3.6

RUN apt-get update -y && apt-get install -y gcc libc-dev

WORKDIR /app
ENV HOME=/app

COPY requirements.txt .
RUN pip3 install -r requirements.txt
EXPOSE 8080

#CMD ["python3", "server.py"]
