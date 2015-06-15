# Dockerfile for nginx in fastcgi mode

Must be used with a fast cgi server (edit default.conf if you want to change the ip, port, etc)

Example (running on port 80):

```
docker run -p 80:80 -v /path/to/the/web/directory/on/host:/var/www/html vivi7865/nginx-fastcgi
```
