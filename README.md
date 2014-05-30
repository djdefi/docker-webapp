docker-webapp
=============

Used to add your webapp to the djdefi/docker-webapp-base image


Based off of djdefi/docker-webapp-base trusted build ( https://github.com/djdefi/docker-webapp-base )



Howto
=============
    git clone https://github.com/djdefi/docker-webapp.git
    cd docker-webapp
    git clone https://github.com/user/yourwebapp.git .
    docker build -t djdefi/docker-webapp .
    docker run -p 8888:80 -t djdefi/docker-webapp
