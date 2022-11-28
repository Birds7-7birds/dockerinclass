
FROM python:3


RUN pip install flask
RUN apt-get update -y

RUN mkdir /app 
WORKDIR /app
COPY ./app .

EXPOSE 5000
CMD ["bash", "maketxt_and_run.sh"]

