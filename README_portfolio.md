# 🌿 Osama Mashhoot — Portfolio Website

A modern, professional, single-file portfolio website for an Agricultural Engineer specialized in Animal Production.

---

## 🚀 How to Open

Simply **double-click** `osama_portfolio.html` to open it in any web browser.
No server, no npm, no build step required.

---

## ✨ Features

| Feature | Details |
|---|---|
| 🌙 Dark/Light Mode | Toggle button in the navbar |
| 📱 Fully Responsive | Works on mobile, tablet, desktop |
| 🎞️ Scroll Animations | Fade-up / fade-left / fade-right on all sections |
| 📊 Animated Skill Bars | Trigger on scroll into view |
| 🔢 Animated Counters | Numbers count up on scroll |
| 📬 Contact Form | With success message feedback |
| 📄 Download CV Button | Hook it to your hosted PDF |
| ↑ Back-to-Top Button | Appears after scrolling 500px |
| 🎨 Green Nature Theme | Sage, mint, beige, forest green palette |
| 🖋️ Premium Typography | Playfair Display + DM Sans |

---

## 🎨 Customization Guide

### 1. Change Name / Title
Search for `Osama` and `Mashhoot` → replace with your full name.
Search for `Agricultural Engineer` → update job title.

### 2. Update Contact Info
Find the `contact-items` section and update:
- University name
- Location
- Specialization

### 3. Link Your CV
Find `downloadCV()` function in the `<script>` tag:
```javascript
function downloadCV() {
  window.open('https://your-cv-link.com/cv.pdf', '_blank');
  // Replace the URL above with your actual hosted PDF link
}
```

### 4. Add Social Media Links
Find `.social-links` section and add `href` to each `.social-btn`:
```html
<a href="https://linkedin.com/in/yourprofile" class="social-btn" target="_blank">in</a>
```

### 5. Update Skill Percentages
Each skill card has `data-pct="90"` — change the number (0–100).

### 6. Add Real Projects
In the `#projects` section, update each `.project-card` with:
- Your real project titles and descriptions
- Actual GitHub/demo links
- Correct technology badges

### 7. Change Colors
At the top of the `<style>` block, edit the `:root` CSS variables:
```css
:root {
  --green: #2d5a1b;     /* Primary green */
  --green2: #4a8c2a;    /* Secondary green */
  --accent: #c8a84b;    /* Gold accent */
  --bg: #f7f4ef;        /* Page background */
}
```

### 8. Add Your Photo
Replace the monogram avatar with an `<img>` tag:
```html
<img src="your-photo.jpg" style="width:100%;height:100%;object-fit:cover;border-radius:50%"/>
```
Place it inside `.avatar-inner` replacing the `.avatar-initial` div.

---

## 📁 File Structure

```
osama_portfolio.html    ← Single self-contained portfolio file
README_portfolio.md     ← This guide
```

---

## 🌐 Hosting Options (Free)

| Platform | Steps |
|---|---|
| **GitHub Pages** | Upload to a repo → Settings → Pages → Deploy |
| **Netlify Drop** | Drag the HTML file to netlify.com/drop |
| **Vercel** | Connect GitHub repo → auto deploy |
| **Google Drive** | Upload + share public link |

---

## 🛠️ VS Code Tips

1. Install **Live Server** extension
2. Right-click the HTML file → "Open with Live Server"
3. Auto-refreshes as you edit

---

*Built with pure HTML, CSS & JavaScript — no frameworks, no dependencies.*
