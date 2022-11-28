
FROM python:3

RUN mkdir /app 

WORKDIR /app

RUN pip install flask
RUN apt-get  update -y
RUN apt-get install -y wget wait-for-it

COPY ./app .

EXPOSE 5000
CMD ["bash", "maketxt_and_run.sh"]

