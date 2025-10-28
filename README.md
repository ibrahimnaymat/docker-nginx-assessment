# this project is simply about creating a custom docker imagethat serves a personalized html file using nginx-1.24  webserver
- the build command to build the image from my docker file is docker build -t nginx:1.24-alpine .
docker run -d -p 8888:80 nginx:1.24-alpine