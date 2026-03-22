# aarushagrawal.me

Personal portfolio website for Aarush Agrawal — CS student at UT Dallas.

Live at: [aarushagrawal.me](https://aarushagrawal.me)

---

## What is this?

A dark, sleek single-page portfolio showcasing my projects, background, and contact info. Built as a pure HTML/CSS/JS file with no frameworks or dependencies — just drop it in a browser and it works.

---

## Tech Stack

- HTML5
- CSS3 (custom properties, animations, grid, flexbox)
- Vanilla JavaScript
- Fonts: [Syne](https://fonts.google.com/specimen/Syne) + [DM Mono](https://fonts.google.com/specimen/DM+Mono) via Google Fonts
- Hosted on: GitHub Pages
- Domain: Namecheap (.me)

---

## How to Run Locally

No build step needed.

1. Clone the repo:
   ```bash
   git clone https://github.com/Aarush49/aarushagrawal.me.git
   ```
2. Open `index.html` in your browser:
   ```bash
   open index.html
   ```
   Or just drag and drop the file into any browser window.

---

## How to Deploy

This site is hosted on **GitHub Pages** with a custom domain via Namecheap.

### GitHub Pages Setup
1. Push `index.html` to the `main` branch
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Click **Save**

### Custom Domain Setup
1. In GitHub Pages settings, enter your domain under **Custom domain** and save
2. In Namecheap **Advanced DNS**, add the following records:

| Type | Host | Value |
|------|------|-------|
| A Record | @ | 185.199.108.153 |
| A Record | @ | 185.199.109.153 |
| A Record | @ | 185.199.110.153 |
| A Record | @ | 185.199.111.153 |
| CNAME Record | www | aarush49.github.io |

3. Wait 10-30 minutes for DNS to propagate

---

## Contact

- Email: aarush040907@gmail.com
- LinkedIn: [agrawalaarush](https://linkedin.com/in/agrawalaarush)
- GitHub: [Aarush49](https://github.com/Aarush49)
