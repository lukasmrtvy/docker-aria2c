# aria2c

## Info:
Based on Alpine:latest

## Usage:
`sudo docker rm -f aria2c ; sudo docker run -d -e RPC_TOKEN=TOKEN -p 6800:6800 -v aria2c:/opt/ -v /opt/downloads:/opt/downloads --name aria2c lukasmrtvy/docker-aria2c`
