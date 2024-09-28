FROM python:3.13.0rc2-slim
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
ENTRYPOINT ["mlflow", "server"]
