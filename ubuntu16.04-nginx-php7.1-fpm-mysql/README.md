# Infomations
## Author
- Name: **Toan Nguyen**
- Github: https://github.com/nguyentoanit
- Facebook: https://www.facebook.com/nguyentoandev

## Dockerfile
- OS: Centos 6.8
- Apache: 2.2.15
- PostgreSQL: 8.4
- PHP: 5.6.32

- Description: Lamp stack with cron service. Auto start Lamp stack when user start container

## A few commom commands
- List cron file:

```
crontab -l
```
- Edit cron file:

```
crontab -e
```
- Start/Stop/Restart apache:

```
service httpd start/stop/restart
```
- Initial PostgreSQL database

```
service postgresql initdb
```
- Start/Stop/Restart Postgresql:

```
service postgresql start/stop/restart

```
