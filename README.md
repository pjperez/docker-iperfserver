# docker-iperfserver
Docker image that connects to Wormhole's overlay network and starts and iPerf server

## Building docker-iperfserver
    
    git clone https://github.com/pjperez/docker-iperfserver
    sudo docker build -t wormhole/docker-iperfserver .

## Running docker-iperfserver
    sudo docker run -t -i --privileged=true wormhole/docker-iperfserver
    
## More info

Read [docker-wormhole](https://github.com/pjperez/docker-wormhole) if you're not familiar with Wormhole's Docker image.