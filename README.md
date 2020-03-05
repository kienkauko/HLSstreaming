Include:  
Config file for nginx  
html file for HLS player  
  
Streaming via ffmpeg: sudo ffmpeg -re -i Downloads/"videoname.mp4" -c:v copy -f flv rtmp://localhost/show/stream  
ffmpeg can restream from other source, as well as do transcoding

HLSplayer can be seen at localhost address, change url to deliver expected video or stream  
Detail: https://docs.peer5.com/guides/setting-up-hls-live-streaming-server-using-nginx/?fbclid=IwAR1J6vPgYUKplDOo1-e3Jp1m8itvHQ1OTZfuerdYCsSt-8mlxxJrFHwe7PQ

