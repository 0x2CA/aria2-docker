# aria2-docker

## use

```
docker pull 0x2ca/aria2
docker run -d --name aria2  --restart always -p 8081:80 -p 6800:6800 -v C:\Users\Zero\Downloads:/data -v D:\aria2:/conf 0x2ca/aria2
```
