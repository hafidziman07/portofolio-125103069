# Personal Portfolio

**Name:** Hafidz Iman Al-Kaits
**Student ID:** 125103069
**Course:** Web Programming

## Overview
A personal portfolio website with three pages (Home & About Me, Projects, and Contact),
featuring a simple blue-and-white design that adapts to mobile and desktop screens.

## Technologies
- Semantic HTML5 (header, nav, main, section, footer)
- Custom external CSS (`css/style.css`)
- **Bootstrap 5.3** via CDN (navbar, grid, card, form, table)

## Folder Structure
```
portofolio-NIM/
|-- index.html    <- home page
|-- proyek.html
|-- kontak.html
|-- css/style.css
|-- img/foto.jpg
`-- README.md
```

## Pages
1. `index.html` — Home (hero + profile photo) and About Me (skills table)
2. `proyek.html` — Projects (six cards, summary table, learning resources)
3. `kontak.html` — Contact (contact information + message form)

## Website on Vercel
https://portofolio-125103069.vercel.app/

## Run Locally
Save this folder in `C:\xampp\htdocs\`, open the XAMPP Control Panel, and start Apache.
Then visit `http://localhost/Portfolio%20Pemrograman%20Web/` (or use the folder name you chose).

## Upload to GitHub
```bash
git init
git add .
git commit -m "Initial portfolio version with Bootstrap 5"
git branch -M main
git remote add origin https://github.com/hafidziman07/portofolio-125103069.git
git push -u origin main
```
