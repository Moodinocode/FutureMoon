# Future Moon

A landing page for **$Future Moon**, a joke memecoin some friends and I talked about launching. I built the site; the coin never existed.

Made in 2022, when I was 16. It's here as the earliest thing I've kept — the first site I put together on my own, during peak memecoin season.

## What's on the page

- A hero section with the coin's logo and tagline ("Beyond the Moon we Rise")
- A four-step **How to Buy** guide — buy BNB, move it to Trust Wallet, swap for Smart Chain BNB, then swap for $Future Moon on PancakeSwap
- A signup modal and a footer with a Telegram link

The buy instructions were written to mirror how BSC token sites looked at the time. There was never a contract address, because there was never a token.

## Built with

Plain HTML and CSS with Bootstrap 5.2.0-beta1, vendored into `vendor/`. No build step — open `index.html` in a browser.

```
index.html
main.css
main.js
assets/     logos and images
vendor/     bootstrap 5.2.0-beta1
```

## Running it

```bash
git clone https://github.com/Moodinocode/FutureMoon.git
cd FutureMoon
```

Then open `index.html` in a browser, or serve it:

```bash
python -m http.server 8000
```

## History

The page was originally built on top of a Bootstrap tutorial template and kept in a repo I was using to learn how to push files to GitHub, so it carried a lot of baggage: the full tutorial template, macOS `__MACOSX` folders, `.DS_Store` files, and JetBrains `.idea` config.

Cleaned up in September 2026 — removed that baggage, moved images into `assets/` and Bootstrap into `vendor/`, and deleted leftover markup from the template that was unreachable (three video modals whose trigger buttons had been commented out). The page itself renders exactly as it did; nothing about the design changed.
