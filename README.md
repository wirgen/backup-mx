# backup-mx
Simple postfix backup mailserver for your Docker containers. Based on Alpine Linux.

## TL;DR

To run the container, do the following:
```
docker run --rm --name backup-mx -e "DOMAIN=example.com HOSTNAME=mx2.example.com MAIN_SERVER=mx.example.com" -p 25:25 wirgen/backup-mx
```