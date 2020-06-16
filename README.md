# mkcert_docker

````
cp /root/certs/rootCA.pem /etc/ssl/certs/
update-ca-certificates --fresh
ls /etc/ssl/certs/ -al | grep 'rootCA.pem'
````
