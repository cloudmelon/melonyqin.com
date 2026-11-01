# Hi there, I'm Mélony - aka [CloudMelon]

This is the source of my personal site: founder, technologist and author.

[![Website](https://img.shields.io/website?label=melonyqin.com&style=for-the-badge&url=https%3A%2F%2Fmelonyqin.com)](https://melonyqin.com)
[![Website](https://img.shields.io/website?label=cvisiona.com&style=for-the-badge&url=https%3A%2F%2Fcvisiona.com)](https://cvisiona.com)
<p>
<a href="https://github.com/cloudmelon" target="_blank"><img alt="Github" src="https://img.shields.io/badge/GitHub-%2312100E.svg?&style=for-the-badge&logo=Github&logoColor=white" /></a>
<a href="https://x.com/MelonyQ" target="_blank"><img alt="X" src="https://img.shields.io/badge/X-%2312100E.svg?&style=for-the-badge&logo=x&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/melony-qin" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://bsky.app/profile/cloudmelon.bsky.social" target="_blank"><img alt="Bluesky" src="https://img.shields.io/badge/bluesky-%230285FF.svg?&style=for-the-badge&logo=bluesky&logoColor=white" /></a>
<a href="https://mastodon.social/@melonyqin" target="_blank"><img alt="Mastodon" src="https://img.shields.io/badge/mastodon-%236364FF.svg?&style=for-the-badge&logo=mastodon&logoColor=white" /></a>
<a href="https://www.youtube.com/@CloudMelonVis" target="_blank"><img alt="YouTube" src="https://img.shields.io/badge/youtube-%23FF0000.svg?&style=for-the-badge&logo=youtube&logoColor=white" /></a>
<a href="https://melonyqin.substack.com/" target="_blank"><img alt="Substack" src="https://img.shields.io/badge/substack-%23FF6719.svg?&style=for-the-badge&logo=substack&logoColor=white" /></a>
<a href="https://www.instagram.com/cloudmelonvis" target="_blank"><img alt="Instagram" src="https://img.shields.io/badge/instagram-%23DD0031.svg?&style=for-the-badge&logo=instagram&logoColor=white" /></a>
<a href="https://www.facebook.com/cloudmelon" target="_blank"><img alt="Facebook" src="https://img.shields.io/badge/facebook-%23326ce5.svg?&style=for-the-badge&logo=facebook&logoColor=white" /></a>
<a href="https://github.com/sponsors/cloudmelon" target="_blank"><img alt="Sponsor" src="https://img.shields.io/badge/sponsor-%23EA4AAA.svg?&style=for-the-badge&logo=githubsponsors&logoColor=white" /></a>
</p>

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

## Support

If my books, talks or open-source work helped you, you can [sponsor me on GitHub](https://github.com/sponsors/cloudmelon).

## License

© 2026 Mélony Y. Qin. All rights reserved. The code is public so the site can be hosted here; the content, design and images are not licensed for reuse.
