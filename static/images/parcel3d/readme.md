To fix corrupt `mp4` files run

```shell
for file in /path/to/folder/*.mp4; do ffmpeg -i "$file" -vcodec h264 "${file%.mp4}_encoded.mp4"; done
```
