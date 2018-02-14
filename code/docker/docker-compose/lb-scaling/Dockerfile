FROM python:2.7
MAINTAINER Carl Lu "yotsuba1022@gmail.com"
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
EXPOSE 8080
CMD [ "python", "app.py" ]