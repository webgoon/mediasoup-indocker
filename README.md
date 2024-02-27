# mediasoup-indocker
This is a sfu media server running in a docker container on a ubuntu server


```sh
    docker build -t ubuntu .
```

Once ran be patient because it will take some time...


Run the following command docker images to see if you see About a minute a go a new REPOSITORY called ubuntu

```sh
    docker images
```

Now You can run it will activate the docker.compose.yml file.

Note: on docker-compose.yml file replace - "/C/nodeworld/mediasoup-indockercontainer:/usr/src"

replace /C/nodeworld/mediasoup-indockercontainer with the document root of your poject to where the docker-compose.yml is located on your local machine.


```sh
    docker-compose up -d
```
