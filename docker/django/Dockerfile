 FROM python:3
 ENV PYTHONUNBUFFERED 1
 RUN mkdir /usr/src/app
 WORKDIR /usr/src/app
 ADD requirements.txt /usr/src/app/
 RUN pip install -r requirements.txt
 ADD . /usr/src/app