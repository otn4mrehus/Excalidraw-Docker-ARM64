# Excalidraw-Docker-ARM64-Version
Excalidraw Docker Compose For  ARM64 [Tested:  Armbian 23.08.0-trunk Bookworm with Linux 6.1.52-ophub]
## Download
````
apt install git && \
git clone https://github.com/otn4mrehus/Excalidraw-Docker-ARM64.git && \
cd Excalidraw-Docker-ARM64
````
## Build Container
````
docker-compose -p 'excalidraw' up --build -d --remove-orphans ## Build Container 
docker-compose -p 'excalidraw' down -v --remove-orphans       ## Remove Container
docker-compose -p 'excalidraw' start     ## Start Container
docker-compose -p 'excalidraw' stop      ## Stop Container
````
## Run Excalidraw
````
http://127.0.0.1:4000
http://domain_address:4000
http://ip_address:4000
````
