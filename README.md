<h1 align="center">Aji Yudha Perwira</h1>

<p align="center">
Software Engineer • Industrial systems, ERP, and desktop tooling
</p>

<p align="center">
<a href="https://kuhlenlabs.web.id">Website</a> •
<a href="https://www.linkedin.com/in/aji-perwira/">LinkedIn</a>
</p>

---

I write software that has to keep working in places where the network is bad and there is nobody around to restart things.

I started in IT support, then system administration and DevOps, and moved into software development from there. That order shaped how I work. I spent a few years being the person who gets called when production breaks, so I think about how something runs before I think about how it is written.

Lately most of my work sits close to hardware: serial ports, weighbridges, race timing sensors, and the web and desktop apps that sit on top of them.

---

## Tech I Work With

**Languages**

Python • TypeScript • Rust

**Web**

SvelteKit • Leptos • WASM • Odoo

**Cross-platform**

Tauri • Flutter • PySide

**Hardware & Protocols**

RS232 Serial • Web Serial API • MQTT • WebSocket • Arduino • Raspberry Pi

**Infrastructure**

Linux • Docker • Nginx • Google Cloud • WireGuard • GitHub Actions

**Databases**

PostgreSQL • SQLite • MongoDB

---

## Featured Work

**Gokart RMS**<br>
`Rust · Tauri 2 · Leptos`

Race timing and leaderboard system for Funderland Indonesia, running at their Medan track. It started as an Angular app reading a lap sensor through the Web Serial API. I rebuilt it as a native desktop app with two windows, one for the operator and one for the trackside display, with SQLite bundled in.

**Weighbridge Data Pipeline**<br>
`MQTT · RS232 · Flutter · Go`

Moves live weight readings from weighbridge hardware into the ERP web app. REST and WebSocket both fell apart on plantation networks, so I moved the transport to MQTT, and later to MQTT over WebSocket so the middleware service was no longer required at all. Stress tested with Clumsy at 2000ms latency, 30% packet loss and 5KB/s bandwidth. Readings still arrived.

**Palm Scale**<br>
`SvelteKit · Web Serial API · PostgreSQL`

A weighbridge management system that runs in the browser. It reads RS232 scale data directly through the Web Serial API, so there is no desktop middleware to install and keep updated on every mill PC, and it keeps recording when the connection to the server drops.

**Pixlet**<br>
`Rust · Leptos · WASM`

Image converter that runs entirely in the browser. JPG, PNG, WebP, GIF, BMP and TIFF. Nothing gets uploaded anywhere, which is good for privacy and also means it costs nothing to host.

**Port Monitor**<br>
`Rust · Tauri 2 · Leptos`

A serial port debugger I built because I got tired of guessing what a scale was actually sending. Auto-detects USB, Bluetooth and PCI ports, shows live readings with millisecond timestamps, and filters by offset, length and excluded characters. Ships for Linux, Windows and macOS.

**Self-hosted OSRM**<br>
`OSRM · Linux · Nginx`

Routing server for a public bus tracking app, deployed on a provincial government infrastructure. The original plan was the Google Maps API. Self-hosting avoided roughly $500 a month in routing costs once usage scaled.

**KuhlenLabs**<br>
[kuhlenlabs.web.id](https://kuhlenlabs.web.id)

My site. Eleven case studies with the longer version of the work above, plus the Odoo ERP suite and the GCP infrastructure I ran for a second-hand marketplace.

---

## GitHub Stats

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=Kuhlen&show_icons=true&hide_border=true&theme=tokyonight" height="165">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kuhlen&layout=compact&hide_border=true&theme=tokyonight" height="165">
</p>

---

<p align="center">
Available for freelance work. Always open to interesting projects and conversations.
</p>
