# slideshow_mp4

Build an MP4 slideshow from a folder of images, with optional fades, background and music.

## Requirements

ffmpeg.

## Use

```
chmod +x slideshow.sh
./slideshow.sh png
./slideshow.sh -d 8 -f 1 -o quotes.mp4 png
./slideshow.sh -d 4 --music track.mp3 photos
```

Made for Debian. Run it from its folder or put it on your `PATH`. Run it with `-h` where supported, or read the comment header at the top of the script.

More Linux tools and write-ups by Ben Santora: [truelinux.pages.dev](https://truelinux.pages.dev/)

## License

MIT - see [LICENSE](LICENSE).
