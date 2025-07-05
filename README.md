# 💖 Happy Anniversary Celebration Page

This is a sweet and interactive web page made to celebrate a special anniversary with fireworks, love messages, background music, and dynamic animations.

![Preview](https://github.com/coderboe/repo-image/blob/master/pimg/anniversary.png)

## 🌟 Features

- 💬 Custom love message
- 📅 Automatically calculates days, months, and years together
- 🎆 Fireworks animation (manual & auto)
- 🎶 Background music with smooth volume fade-in
- 🧡 Heart-shaped fireworks!
- 💻 Responsive design
- 🎨 Stylish with animated background and GSAP effects

## 📁 Project Structure

 anniversary/
-    ├──README.md
-    ├── index.html  # Main page
-    └── assets/
     -    ├── css/
     -    │   └── style.css  # Styling (pink theme, animations)
     -    ├── images/
     -    │   ├── love.jpg   # icon image
     -    │   ├── bf.jpg     # Boyfriend image
     -    │   └── gf.jpg     # Girlfriend image
     -    ├── js/
     -    │   ├── fireworks.js  # Canvas fireworks engine
     -    │   ├── music.js      # music and counts days
     -    │   └── script.js     # GSAP
     -    └── music/music.mp3  # Background music
     



## 🛠 How to Use

1. **Download or Clone**
   ```bash
   git clone https://github.com/coderboe/anniversary.git
   cd anniversary
2.**Open in Browser**
Simply open index.html in any modern browser (Chrome, Edge, Firefox).

3.**Click the 🎉 Start Celebration button to:**

- Start music

- Show fireworks

- Animate the page!

## ✏️ Customization

| Element          | File                      | How to Edit                                         |
| ---------------- | ------------------------- | --------------------------------------------------- |
| Names & Text     | `index.html`              | Edit the `<h1>`, `<p>`, etc.                        |
| Photos           | `bf.jpg`, `gf.jpg`        | Replace with your own                               |
| Start Date       | `music.js`                | Update: `const startDate = new Date("YYYY-MM-DD");` |
| Music            | `music.mp3`               | Replace file but keep same name                     |
| Fireworks Colors | `fireworks.js`            | Change array in `randomColor()`                     |
| GSAP Animations  | `index.html` or custom JS | Modify or add GSAP effects                          |

## 🔧 Dependencies
- [GSAP v3.12.5](https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js) – for animations

- No build tools required – pure HTML, CSS, JS

## 📦 Hosting
You can publish this on GitHub Pages or any static hosting service.

**GitHub Pages Quick Setup**

1.Push this project to GitHub

2.Go to your repo → Settings → Pages

3.Set source to main branch and /root

4.Visit https://coderboe.github.io/anniversary/

## ❤️ Credits
Made with love by Lu Taw for Yunn 💑
Includes free-to-use fireworks canvas logic and GSAP animations.


