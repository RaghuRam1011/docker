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
docker image inspect ubuntu
```