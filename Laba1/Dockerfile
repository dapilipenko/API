FROM python:3.10
EXPOSE 5000
WORKDIR /Laba1
RUN pip install flask
COPY . .
CMD ["flask", "run", "--host", "127.0.0.0"]