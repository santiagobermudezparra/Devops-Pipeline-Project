FROM python:latest

WORKDIR /app


#add more layers
RUN touch file1.txt
RUN echo "hello" > file2.txt
RUN mkdir -p /app/test


COPY . /app

CMD ["python", "main.py"]
