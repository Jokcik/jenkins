## Build

Сборка
```bash
docker build -t jenkins .
docker run --name myjenkins --rm -p 8082:8080 -p 50001:50001 jokcik/jenkins
```
