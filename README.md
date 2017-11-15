# Docker Wordpress + Mysql + Traefik(Reverse Proxy) + Volumerize(Backup)

**Warning!** This image needs Traefik overlay network with name **'traefik-net'**

Needed Environments (with e.g.)
```dotenv
MYSQL_ROOT_PASSWORD=PASSWORD
TRAEFIK_FRONTEND_RULE=Host:sample.com
VOLUMERIZE_TIMEZONE=Asia/Seoul
VOLUMERIZE_JOBBER_TIME=0 0 3 * * *
```
