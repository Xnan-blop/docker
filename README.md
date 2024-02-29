Run these commands in terminal and go to http://localhost:8080

docker build . -t sample-flask-app:v1

docker container run -d -p 8080:8080 sample-flask-app:v1
