
TLS 1.2以外の通信を無効にする。
```
$ echo "SSLProtocol -all +TLSv1.2" >> /etc/apache2/apache2.conf
$ supervisorctl restart apache
```
