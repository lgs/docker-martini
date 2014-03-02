docker-martini
==============

Dockerfile for Martini/GOLANG 1.2 on Ubuntu 13.10 (Saucy Salamander) - VERSION 1.0

## Use 

    $ docker pull lgsd/docker-martini
    $ docker run -d -p 3000:3000 -name martini -t lgsd/docker-martini:latest
    23f1c41a7e8b6bfc7b9135fd1a37a234d4536d5da876b6f50558b3385564027c
    $ docker ps -a
    CONTAINER ID        IMAGE                       COMMAND             CREATED              STATUS              PORTS                    NAMES
    23f1c41a7e8b     lgsd/docker-martini:latest   go run server.go    About a minute ago   Up About a minute   0.0.0.0:3000->3000/tcp   martini            
    # You will now have a Martini webserver running on localhost:3000

    $ curl localhost:3000
    Hello world!

## Copyright

Copyright (c) 2013-2014 Luca G. Soave

