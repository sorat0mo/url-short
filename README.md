[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![](https://img.shields.io/badge/Original_Project-60ed5a)](https://github.com/nelsontky/gh-pages-url-shortener)

# 🔗 GitHub Pages URL Shortener

This is a minimal URL shortener that can be entirely hosted on GitHub pages. Changes are made upon the original code.

**Warning: I solicited help from GitHub Copilot when modifying the original project for my use.**

Original project is here: [https://github.com/nelsontky/gh-pages-url-shortener](https://github.com/nelsontky/gh-pages-url-shortener)

## 👨‍🏫 Demo

1. [https://go.karsten.ws/mastodon](https://go.karsten.ws/mastodon) brings you to my mastodon profile.

2. Appending a `?` at the end allows you to preview the destination, a QR code is also displayed for scanning with phone.

![](/assets/feature1.png)

3. To prevent unauthorized usage, the script checks for issue by authorized user. An error message will be displayed if unauthorized link is detected.

## ☕️ Features

1. GitHub Issues provide database-esque feature. No reliance on external databases.

2. Minimal deployment difficulty. It's just 2 webpages. You can host it with GitHub Pages or similar services.

3. Editing the original Issue edits the URL. Some short url services charges for this. Insane, right?

## Thanks
This modification is impossible without the help from GitHub user [river](https://github.com/nelsontky/gh-pages-url-shortener/pull/112) and [wmz1024](https://github.com/nelsontky/gh-pages-url-shortener/pull/89)

## Hosting
I host mine on vercel, in order to serve secure headers. You can still host it on GitHub Pages.

## Other Questions
Please check the original project if you have further questions.
