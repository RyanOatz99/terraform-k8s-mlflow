FROM python:3.14.2-slim
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
ENTRYPOINT ["mlflow", "server"]
