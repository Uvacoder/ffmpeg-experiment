# misc

```
# download blender bunny movie for testing ((c) copyright 2008, Blender Foundation / www.bigbuckbunny.org)
yt-dlp -f 249 -o misc/test-original.webm https://www.youtube.com/watch?v=YE7VzlLtp-4
ffmpeg -ss 00:00:00 -to 00:00:20 -i misc/test-original.webm -c copy misc/test.webm
wget -O misc/test.jpg https://i.ytimg.com/vi/YE7VzlLtp-4/maxresdefault.jpg
```
