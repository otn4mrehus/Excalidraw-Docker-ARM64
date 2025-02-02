# Excalidraw-Docker-ARM64-Version
Excalidraw Docker Compose For  ARM64
## Download
````
apt install git \
gic clone https://github.com/otn4mrehus/Excalidraw-Docker-ARM64/.git
cd Excalidraw-Docker-ARM64
````
## Build Container
````
docker-compose 'excalidraw' up --build -d --remove-orphans ## Build Container 
docker-compose 'excalidraw' down -v --remove-orphans       ## Remove Container
docker-compose 'excalidraw' start     ## Start Container
docker-compose 'excalidraw' stop      ## Stop Container
````
## Run Excalidraw
````
http://127.0.0.1:4000
http://domain_address:4000
http://ip_address:4000
````
