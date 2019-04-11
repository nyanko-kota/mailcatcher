# mailcatcher
[![Docker Automated build](https://img.shields.io/docker/automated/nyankokota/mailcatcher.svg?style=flat)](https://hub.docker.com/r/nyankokota/mailcatcher/)
[![Docker Pulls](https://img.shields.io/docker/pulls/nyankokota/mailcatcher.svg?style=flat)](https://hub.docker.com/r/nyankokota/mailcatcher/)
### How to use

```
    mailcatcher:
      image: nyankokota/mailcatcher:latest
      container_name: 'mailcatcher'
      ports:
          - "8082:8082"
          - "1025:1025"
      restart: always
```
