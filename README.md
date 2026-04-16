# Javascript QRCode Generator

A simple frontend Javascript QRCode Generator based on [davidshimjs/qrcodejs](https://github.com/davidshimjs/qrcodejs).  
Live demo: 👉 [https://darojatun.github.io/qr/](https://darojatun.github.io/qr/)

---

## About

This project is a personal implementation of a QRCode generator using the great open-source library [`qrcodejs`](https://davidshimjs.github.io/qrcodejs/).  
I honestly don’t know much about coding — especially Javascript — but I needed a simple, clean, and ad-free QRCode generator that I could use easily for other projects.

So, I created this frontend page to generate QR codes dynamically.  
You can use a URL like:

👉 [https://darojatun.github.io/qr/?gen=your_text_here](https://darojatun.github.io/qr/?gen=your_text_here)

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
- Accepts `gen=` query parameter for quick use in external links
- Personalize title by `gh1=`
- Icons were simplified from Font Awesome to inline SVGs to save space and dependencies

---

## UI Design

This frontend also uses **Flat 3.0**, a free login form template created by **Andy Tran**, adapted from his work featured on Creative Tim:  
👉 [https://www.creative-tim.com/blog/tw-components/free-form-templates-code-included/](https://www.creative-tim.com/blog/tw-components/free-form-templates-code-included/)

Big thanks to the original designer for such a clean and elegant layout.

---

## Acknowledgements

Big thanks to anyone who recognizes the code or the page — much of it is built upon the work of others, especially:
- [David Shim](https://github.com/davidshimjs/qrcodejs) for `qrcodejs`
- [Andy Tran](https://www.creative-tim.com/blog/tw-components/free-form-templates-code-included/) for the Flat 3.0 template

I just simplified the frontend for personal and public use.

---

## Demo

-👉 [https://darojatun.github.io/qr/](https://darojatun.github.io/qr/)
-👉 [https://jkt.djatun.com/qr/?h1=My%20WiFi%20HotSpot&gen=http://mywifi.id/login?username=UsEr&password=PasWorD]
