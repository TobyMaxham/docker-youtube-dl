# tmaxham/youtube-dl

This Docker-Image provides a quick way to use the [youtube-dl](https://wiki.ubuntuusers.de/youtube-dl/) package.

Download MP4/MP3 in current folder.
```
docker run --rm -v $PWD:/downloads tmaxham/youtube-dl YourVideoURL
docker run --rm -v $PWD:/downloads tmaxham/youtube-dl -x --audio-format mp3 --audio-quality 0 YourVideoURL
```
