FROM python:3

RUN pip install flask && pip install flask_pymongo

COPY . .

RUN cd microservices-k8s/flask-api

ENTRYPOINT ["python", "microservices-k8s/flask-api/app.py"]

