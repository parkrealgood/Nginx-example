## Nginx 컨테이너 실행
```bash
docker build -t nginx-example .
docker run --name nginx -p 80:80 -d nginx-example
```
