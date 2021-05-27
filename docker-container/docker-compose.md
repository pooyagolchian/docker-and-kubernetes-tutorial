### Docker compose

-   `docker-compose up`
-   `docker-compose down`

### Docker compose yml file

Sample file of docker-compose.yml file.

```bash
veresion: '3'
service:
    web:
      build:
      port:
      -   "5000":"5000"
      volumns:
      -   . :/code
    redis:
      image: "redis:alpine"
```
