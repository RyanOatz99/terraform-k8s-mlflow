FROM python:3.9.11-slim
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
ENTRYPOINT ["mlflow", "server"]
