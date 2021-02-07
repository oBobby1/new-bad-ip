**New Bad IP**

If you want to use this please do the following:

1. `cd /etc/nginx/`
2. wget the raw github file from [here](https://raw.githubusercontent.com/xxdjbobbyxx/new-bad-ip/main/deny.conf)
3. `nano nginx.conf`
4. `include /etc/nginx/deny.conf;` in the http server block
5. `nginx -t && systemctl reload nginx`

Your welcome guys and girls xxxx
