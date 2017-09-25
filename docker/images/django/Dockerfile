FROM python:2.7.13

ADD ./example/requirements.txt /usr/local/code/requirements.txt

WORKDIR /usr/local/code

RUN pip install -r requirements.txt

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
