# Tammilanit
Configuration files to our LAN-party

## LANCache
See https://lancache.net/ for more documentation. Here's just my own config and notes.
Start it with 
```c
sudo docker-compose up -d --remove-orphans
```
Stop with
```c
sudo docker-compose down
```
see logs
```c
tail -100f lancache/logs/access.log
```

## Pfsense
Pfsense is configured with 4 Internet connection. One for LANCache, one of odd client, one for even clients, and then there's one extra.
