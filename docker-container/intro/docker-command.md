### Docker command

-   `docker pull <image-name>`
-   `docker image ls`
-   `docker pull nginx`
-   `docker run -d -p 80:80 nginx (-d: run as backgroud | -p: port)`
-   `docker run -d -p 80:443 nginx`
-   `docker container ls`
-   `docker container ls --all`
-   `docker ps -a`
-   `docker image ls --all`
-   `docker run -it -p 80:80 nginx`
-   `docker container log <id>`
-   `docker exec <container-name-or-id> <bash-command>`
-   `docker exec afbg ls`
-   `docker exec -it <container-id> /bin/bash`
-   `docker container stop <id>`
-   `docker container start <id>`
-   `docker container rm <id>`
-   `docker image rm <id-or-name>`
-   `docker image rm nginx`
