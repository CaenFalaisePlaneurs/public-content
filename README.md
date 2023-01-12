# caenfalaiseplaneurs.fr public content

## Encoding

```bash
brew install ffmpeg
```

```bash
ffmpeg -i intro-site-cfp.mp4 intro-site-cfp.webm
```

```bash
ffmpeg -i intro-site-cfp.mp4 intro-site-cfp.ogg
ffmpeg -i intro-site-cfp.mp4 -c:v libtheora -q:v 7 -c:a libvorbis -q:a 4 intro-site-cfp2.ogg
```

Use releases.

See [caenfalaiseplaneurs.fr](https://caenfalaiseplaneurs.fr)
