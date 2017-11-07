# typecho-docker

### mysql support
``
docker exec -it typecho docker-php-ext-install  -j$(nproc) pdo pdo_mysql
``

```docker restart typecho```
