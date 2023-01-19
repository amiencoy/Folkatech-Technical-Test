# Folkatech-Technical-Test
untuk run container ini, gunakan command sebagai berikut
```
docker-compose build --pull --force-rm 
#command untuk mendownload stagging container

docker-compose up -V -d 
#mengaktifkan continer (akses localhost di port 80)

docker-compose down -V --rmi local 
#menonaktifkan container
```
