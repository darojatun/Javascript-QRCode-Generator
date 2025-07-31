# Javascript QRCode Generator

A simple frontend Javascript QRCode Generator based on [davidshimjs/qrcodejs](https://github.com/davidshimjs/qrcodejs).  
Live demo: [https://darojatun.github.io/qr/](https://darojatun.github.io/qr/)

---

## About

This project is a personal implementation of a QRCode generator using the great open-source library [`qrcodejs`](https://davidshimjs.github.io/qrcodejs/). I honestly don’t know much about coding — especially Javascript — but I needed a simple, clean, and ad-free QRCode generator that I could use easily for other projects.

So, I created this frontend page to generate QR codes dynamically. You can use a URL like:

https://darojatun.github.io/qr/?gen=your_text_here


And it will automatically show the QR code for `your_text_here`.

This makes it useful for many applications, such as:
- Sharing WiFi passwords via QR codes on Telegram
- Hotspot login pages for MikroTik
- Dynamic QR payments like QRIS in Indonesia
- And many more creative uses

---

## Features

- Clean, minimal interface
- No ads, no tracking
- Works entirely in the browser
- Accepts `?gen=` query parameter for quick use in external links
- Icons were simplified from Font Awesome to inline SVGs to save space and dependencies

---

## Acknowledgements

Big thanks to anyone who recognizes the code or the page — much of it is built upon the work of others, especially the original author of `qrcodejs`. I just simplified the frontend for personal and public use.

---

## Demo

👉 [https://darojatun.github.io/qr/](https://darojatun.github.io/qr/)
