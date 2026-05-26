# Daily Learning

## Morning Planning

- [ ] Check out the GitHub blog
- [ ] Learn about GitHub Pages
- [ ] Commit my first blog post


## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org/)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
