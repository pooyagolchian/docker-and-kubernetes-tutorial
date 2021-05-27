### Persist storage volumes

This file is about MySql presist data.

### Docker persist storage

-   `docker volume ls`
-   `docker volume create mysql-data`
-   `docker volume ls`
-   `docker volume inspect mysq;-data`
-   `ls /var/lib/docker/volumes/mysql-data/_data`

### Persist Strorage example with MySql

-   `docker run --name pooya-mysql -v mysql-data:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=mypasswd -d mysql:latest`
-   `docker exec -it pooya-mysql` /bin/bash
-   `cd /var/lib/mysql`
