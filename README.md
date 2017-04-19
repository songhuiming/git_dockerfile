1. install from the dockerfile
```
docker build -t shmhub/dl-docker:cpu -f Dockerfile.cpu.dl_class .
```

2. modify the .keras/keras.json file

3. start the dl-docker
```
docker run -it -p 8888:8888 -p 6006:6006 -v $(pwd):/root/sharedfolder shmhub/dl-docker:cpu bash
```
