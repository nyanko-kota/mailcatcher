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
