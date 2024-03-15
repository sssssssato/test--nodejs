# test Node.js

## Docker立ち上げ
docker-compose build --no-cache  
docker-compose up -d

---または---  
docker-compose up --build -d

## Doker内のサーバに入る
docker-compose exec -it nodejs sh

## Node.js Serverの立ち上げ
node server.js  
<http://127.0.0.1:3000/>
