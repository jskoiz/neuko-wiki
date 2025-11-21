# Media Folder

This folder contains media assets for the Neuko Wiki.

## Structure

- **`videos/`** - Video files and embedded video content
- **`images/`** - Images, screenshots, and visual assets

## Usage

### Embedding Videos

For direct video files, use HTML in markdown:

```html
<video controls width="100%">
  <source src="../media/videos/post-2.mp4" type="video/mp4">
</video>
```

For X/Twitter embeds, use Twitter's embed code:

```html
<blockquote class="twitter-tweet">
  <p lang="en" dir="ltr">we&#39;re watching</p>
  &mdash; neuko (@neukoai) 
  <a href="https://x.com/neukoai/status/1977763395408429229">October 13, 2025</a>
</blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
```

### Embedding Images

Use standard markdown image syntax:

```markdown
![Description](../media/images/screenshot.png)
```

## File Naming Convention

- Videos: `{context}_{description}.mp4`
- Images: `{context}_{description}.png` or `.jpg`

## Notes

- Keep file sizes reasonable for web viewing
- Use compressed formats when possible
- For X/Twitter videos, embedding via Twitter's embed code is recommended over downloading and hosting

