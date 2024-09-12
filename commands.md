To list running containers 

```
docker ps
```

To decode the encrypted data

```
echo -n cmFnaHU0MjA6UmFtZ2h1QDMyMQ== | base64 -d
```

if we want to  know the starting point of server (ubuntu,nginx...etc)
```
docker image inspect u


how to pass env varibles to docker container there are two ways 

```
docker run --name mycont -e MY_VAR=raghu myenv:v1

```

```
docker run --name mycont --env-file .env myenv:v3
```