#### Building Docker Image.

```
docker-compose up --build -d web
docker tag docker-demo_web boonchu/hello-web-node
docker login
docker push boonchu/hello-web-node
```
