# Level One Header

## Morning planning
- [ ] check out blog for topic ideas
- [ ] learn about github pages
- [ ] convert my first blog post into a webpage

## Review

Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
