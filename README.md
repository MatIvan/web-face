# WebFace
Very simple web page for my home server.

## Run on docker

```bash
docker build -t my-apache2 .
docker run -d --restart=always --name web-face -p 80:80 my-apache2
```
