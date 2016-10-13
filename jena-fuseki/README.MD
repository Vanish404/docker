##### jena-fuseki image based on Alpine:

```bash
docker pull stain/jena-fuseki:latest
docker run --name fuseki-latest -it -p 3030:3030 -e ADMIN_PASSWORD=admin -d stain/jena-fuseki:latest
docker start fuseki-latest
```
