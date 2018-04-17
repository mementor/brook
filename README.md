```
sudo docker run --name brook_socks --restart always -d -p 5555:5555 mentor/brook socks5 -l :5555 -i 0.0.0.0 --password password --username username
```