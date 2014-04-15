```
docker run -d -p 9001:80 \
  --name legacy \
  -v /home/core/shared/legacy/sites-enabled:/etc/apache2/sites-enabled:ro \
  -v /home/core/shared/log/legacy:/var/log/apache2 \
  zajca/apache-php5.4
```
