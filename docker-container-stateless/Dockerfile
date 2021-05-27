FROM alpine:latest
RUN apk update && apk add nodejs
RUN mkdir -p /usr/src/app
COPY ./app.js /usr/src/app
WORKDIR /usr/src/app
EXPOSE 80
CMD ["node", "app.js"]