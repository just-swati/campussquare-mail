# mail.campussquare.in

Sends anyone who opens **https://mail.campussquare.in** (any path) to the Zoho Mail login at https://mail.zoho.com, where the campussquare.in mailboxes (e.g. info@campussquare.in) are hosted.

- Hosted on GitHub Pages from `main`; `index.html` and `404.html` are the same redirect page.
- DNS at GoDaddy: `CNAME  mail  →  just-swati.github.io`
- The website itself lives in [`just-swati/campussquare`](https://github.com/just-swati/campussquare).

To point it somewhere else, change `https://mail.zoho.com/` in both HTML files (three places each) and push.
