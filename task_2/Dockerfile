FROM python:3.10

WORKDIR HW_docker

COPY . .

RUN pip install -r requirements.txt

EXPOSE 5050

CMD ["python3", "manage.py", "runserver", "0.0.0.0:5050"]