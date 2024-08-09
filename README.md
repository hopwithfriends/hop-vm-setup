# How to Run

#### 1.How to get the Image:

```
docker run --privileged --shm-size 1g -d -p 8080:10000 -e VNC_PASSWD=password -e PORT=10000 -e AUDIO_PORT=1699 -e WEBSOCKIFY_PORT=6900 -e VNC_PORT=5900 -e SCREEN_WIDTH=1024 -e SCREEN_HEIGHT=768 -e SCREEN_DEPTH=24 thuonghai2711/ubuntu-novnc-pulseaudio:20.04
```

#### 2. launch fly.io (Make sure you have done the fly installation)

On the same folder of the fly.toml run the following command:

``flyctl launch``

---


