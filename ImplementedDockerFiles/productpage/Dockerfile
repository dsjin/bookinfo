FROM python:3.7-alpine
WORKDIR /usr/src/app/
COPY . /usr/src/app/
RUN apk update && apk add gcc libc-dev g++
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 8080
CMD ["python", "productpage.py", "8080"]