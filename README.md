npm init
npm i express
node server.js
docker build --tag node-docker:1.0.0 .
docker run -p 8000:80 --name node-docker-manager --memory 512m --cpus="2" node-docker:1.0.0