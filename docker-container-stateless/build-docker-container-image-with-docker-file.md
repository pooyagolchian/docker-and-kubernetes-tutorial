### Build Docker container image with docker files

-   Make docker file and add command for docker
-   `docker image build -t hello-world:v2.0 .`
-   `docker build -f ./Dockerfile -t pooyagolchian/hello-world:v2.0 .`
-   `docker image ls`
-   `docker container run -d -p 80:80 pooyagolchian/hello-world:v2.0`
