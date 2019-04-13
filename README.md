# streamnginx
ffmpeg -i /dev/video0 -framerate 1 -video_size 720x404 -vcodec libx264 -maxrate 768k -bufsize 8080k -vf "format=yuv420p" -g 60 -f flv rtmp://example.com:8081/hls/live
