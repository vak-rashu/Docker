FROM python:3.12-alpine AS build
WORKDIR /app
RUN pip3 install flask
COPY . .
EXPOSE 8080
CMD ["python3", "app.py"]
 
