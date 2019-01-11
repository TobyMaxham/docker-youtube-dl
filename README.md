# tmaxham/youtube-dl

This Docker-Image provides a quick way to use the [youtube-dl](https://wiki.ubuntuusers.de/youtube-dl/) package.

## Usage
Download MP4/MP3 in current folder.
```
docker run --rm -v $PWD:/downloads tmaxham/youtube-dl YourVideoURL
docker run --rm -v $PWD:/downloads tmaxham/youtube-dl -x --audio-format mp3 --audio-quality 0 YourVideoURL
```

## Test
~~This Images was testet with Docker for [DigitalOcean](https://m.do.co/c/5332851bbf0f).~~
