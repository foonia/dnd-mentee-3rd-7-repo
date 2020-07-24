FROM python:3

ENV TZ Asia/Seoul

COPY requirements.txt /tmp/

RUN python3 -m pip install --upgrade pip
RUN pip3 install -r /tmp/requirements.txt

ADD . /app
WORKDIR /app

# CMD ["python3","manage.py","runserver","0.0.0.0:8000"]
