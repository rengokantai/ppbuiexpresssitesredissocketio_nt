# ppbuiexpresssitesredissocketio_nt
```
docker run --name rediscourse -p 13679:6379 -d redis:3.2.4
docker run -it --link rediscourse:redis --rm redis redis-cli -h redis -p 6379
docker stop rediscourse
docker start rediscourse
```
