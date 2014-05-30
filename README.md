docker-webapp
=============

Use this to add your apache2+php5 based webapp to the djdefi/docker-webapp-base image


Build from djdefi/docker-webapp-base trusted build ( https://github.com/djdefi/docker-webapp-base )



How to add your own application
=============
    git clone https://github.com/djdefi/docker-webapp.git
    cd docker-webapp
    git clone https://github.com/user/yourwebapp.git app
    docker build -t djdefi/docker-webapp .
    docker run -p 8888:80 -t djdefi/docker-webapp
