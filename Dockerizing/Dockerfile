FROM python:3.9

WORKDIR /src

COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY ./Dockerizing_ML.py .

CMD ["python", "Dockerizing_ML.py"]