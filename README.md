# docker-alpine
Docket alpine with php

Make the image
 docker build -t NAME_IMAGE ./

 Run container
 docker run -d --name NAME_CONTAINER -p 9092:80 -v "/$(pwd)/FOLDER_PROJECT:/usr/share/nginx/html" NAME_IMAGE