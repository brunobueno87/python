FROM python:3.10.12
WORKDIR /app

COPY app/ app
COPY app/index.html /app/index.html
ENTRYPOINT [ "python3" ]
CMD [ "app/app.py" ]
