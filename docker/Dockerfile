FROM python:3.13.0b4-slim
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
ENTRYPOINT ["mlflow", "server"]
