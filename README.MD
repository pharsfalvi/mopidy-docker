# mopidy-docker
Docker image for the mopidy music service

#Build

```
sudo docker build -t pharsfalvi/mopidy:latest .
```


#Run it with 
```
sudo docker run -v /dev/snd:/dev/snd --privileged -p 6680:6680 -v /usr/share/sounds/alsa/:/var/media -d pharsfalvi/mopidy:latest
```
