# Docker Container Nginx HTTP/2 Server Push

```shell
docker container run -d -p 8080:80 -p 8081:443 --rm --name mynginx --volume "$PWD/html":/usr/share/nginx/html --volume "$PWD/conf:/etc/nginx" nginx
```
