FROM python:3.12-alpine

WORKDIR /app

COPY ./requirement.txt ./

RUN pip install -r requirement.txt

COPY . .

EXPOSE 8080

ENTRYPOINT ["python","web-app/app.py"]
