# trale97.github.io

Personal academic website of **Tra Le**, PhD candidate at the Department of Methodology and Statistics, Tilburg University.

🌐 **Live site:** https://trale97.github.io

## Built with

This site is built from the [al-folio](https://github.com/alshedivat/al-folio) template, a Jekyll starter for academic websites by Maruan Al-Shedivat and contributors, and is hosted on [GitHub Pages](https://pages.github.com/).

The al-folio template is released under the MIT License; its license is kept in [`LICENSE`](LICENSE).

## Where things live

| What                                       | File                        |
| ------------------------------------------ | --------------------------- |
| Name, site settings, site icon             | `_config.yml`               |
| Homepage bio, interests, education         | `_pages/about.md`           |
| Profile photo                              | `assets/img/prof_pic.jpg`   |
| Social links under the photo               | `_data/socials.yml`         |
| News items                                 | `_news/` (one file per item) |
| Publications list                          | `_pages/publications.md`    |
| CV page                                    | `_pages/cv.md`              |
| Homepage layout (customized from al-folio) | `_layouts/about.liquid`     |

## Updating the site

Edit the files above, then commit and push to `main`:

```bash
git add <changed files>
git commit -m "Describe the change"
git push origin main
```

The **Deploy site** GitHub Action rebuilds the site and publishes it to the `gh-pages` branch; changes appear on the live site a few minutes later.
