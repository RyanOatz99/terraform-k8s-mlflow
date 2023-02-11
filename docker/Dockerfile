FROM python:3.12.0a5-slim
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
ENTRYPOINT ["mlflow", "server"]
