[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

# 🔗 GitHub Pages URL Shortener

This is a minimal URL shortener that can be entirely hosted on GitHub pages. Changes are made upon the original code.

**Warning: I solicited help from GitHub Copilot when modifying the original project for my use.**

Original project is here: [https://github.com/nelsontky/gh-pages-url-shortener](https://github.com/nelsontky/gh-pages-url-shortener)

## Usage

1. [https://go.karsten.ws/mastodon](https://go.karsten.ws/mastodon) brings you to my mastodon profile.

2. Appending a `?` at the end allows you to preview the destination, a QR code is also displayed for scanning with phone.

![](/assets/feature1.png)

Quick example:
- Issue title: https://example.com/landing
- Issue body (for custom slug): summer-sale
- Labels: active
- Issue ID: 1 (automatically assigned by GitHub)
- Visit: https://your-domain/summer-sale or https://your-domain/1
- Preview-only view: https://your-domain/summer-sale? or https://your-domain/1?

3. To prevent unauthorized usage, the script checks for issue by authorized users. An error message will be displayed if unauthorized link is detected.

## Label based link control
By applying labels to issues, you can control the link's statues.

Supported labels(case-insensitive):
- active: allows redirection(mandatory)
- disabled: blocks redirection and throws an error message
- preview-only: shows the link and QR but never auto redirect

If there is no label present, legacy behavior kicks in, only redirect when an issue is closed.

## Other Features

1. GitHub Issues provide database-esque feature. No reliance on external databases.

2. Minimal deployment difficulty. It's just 2 webpages. You can host it with GitHub Pages or similar services.

3. Editing the original Issue edits the URL. Some short url services charges for this. Insane, right?

## Thanks
This modification is impossible without the help from GitHub user [river](https://github.com/nelsontky/gh-pages-url-shortener/pull/112) and [wmz1024](https://github.com/nelsontky/gh-pages-url-shortener/pull/89)

## Hosting
I host mine on vercel, in order to serve secure headers. You can still host it on GitHub Pages.

## Other Questions
Please check the original project if you have further questions.
