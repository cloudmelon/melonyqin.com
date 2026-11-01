# melonyqin.com

Personal site of **Mélony Y. Qin**: founder, technologist and author. Live at **https://melonyqin.com**.

One static page, plain HTML and CSS, no build step and no JavaScript framework. Hosted on GitHub Pages.

## What's here

| File | Purpose |
|---|---|
| `index.html` | The whole site: markup, styles, Open Graph tags and JSON-LD `Person` schema |
| `assets/mq-icon.svg` | Favicon ("MQ" monogram) |
| `assets/og-image.png` | Link preview image, 1200×630 |
| `robots.txt`, `sitemap-main.xml` | For search engines |
| `CNAME` | Custom domain for GitHub Pages |
| `.nojekyll` | Serve the files as they are, without Jekyll |

## Preview locally

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Update the site

Edit `index.html`, then commit and push to `main`. GitHub Pages publishes within a minute or two.
When the content changes, update `<lastmod>` in `sitemap-main.xml` as well.

## Elsewhere

[GitHub](https://github.com/cloudmelon) · [LinkedIn](https://www.linkedin.com/in/melony-qin/) · [X](https://x.com/MelonyQ) · [Bluesky](https://bsky.app/profile/cloudmelon.bsky.social) · [Mastodon](https://mastodon.social/@melonyqin) · [AI Entrepreneurs Weekly](https://melonyqin.substack.com/) · [Books](https://www.amazon.com/stores/Melony-QIN/author/B07H5L7M9M)

## Support

If my books, talks or open-source work helped you, you can [sponsor me on GitHub](https://github.com/sponsors/cloudmelon).

## License

© 2026 Mélony Y. Qin. All rights reserved. The code is public so the site can be hosted here; the content, design and images are not licensed for reuse.
