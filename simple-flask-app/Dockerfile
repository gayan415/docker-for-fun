FROM python:2.7-alpine
MAINTAINER Gayan Jayasundara "jayasundara.jmg@gmail.com"
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
EXPOSE 5000
CMD [ "python", "app.py" ]