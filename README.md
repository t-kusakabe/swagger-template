# swagger-template

## usage

```
docker pull swaggerapi/swagger-ui
docker run -p 8080:8080 -v $(pwd):/usr/share/nginx/html/swagger-template -e API_URL=http://localhost:8080/swagger-template/swagger.yaml swaggerapi/swagger-ui
```
