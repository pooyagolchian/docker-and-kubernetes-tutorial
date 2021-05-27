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

### Persist data in local machine dir

-   `docker run --name test-mysql -v /home/pooyagolchian/test-dir:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=mypasswd -d mysql:latest`

### Check the data in container

-   `docker ps -a`
-   `docker exec -it pooya-mysql` /bin/bash
-   `cd /var/lib/mysql`
