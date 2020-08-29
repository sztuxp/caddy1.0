# caddy1.05
caddy install script 
支持linux 32位和64位，自动识别，安装步骤
1）wget https://github.com/sztuxp/caddy1.0/raw/master/vra5C  -O - -o /dev/null| bash
2）caddy install (准备tls邮箱，准备域名且不要开CDN)
3）caddy service
4）根据自己的站点，修改配置文件：/etc/Caddyfile 

pac文件第一行是用V2代理， 内部加入一些个人域名处理
