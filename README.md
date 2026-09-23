# 🌐 Md Aminul Haque — 3D Developer Portfolio

An interactive, single-file 3D portfolio built with **Three.js**, vanilla **JavaScript**, and **CSS**.
The background is a living holographic neural network that reshapes itself as you scroll.

**Live demo:** _add your GitHub Pages link here_
**Author:** [Md Aminul Haque](https://github.com/aminul821) · MCA @ NIT Agartala (NIMCET AIR 736)

---

## ✨ Highlights

- **One file, zero build step.** Everything (HTML, CSS, JS, shaders) lives in `index.html`.
- **Real 3D**, not videos or images — nodes, lines, pulses, and shaders rendered live by WebGL.
- **Responds to you** — the network reacts to the cursor, drag, and clicks.
- **Fast** — no heavy post-processing, so it stays smooth on laptops and phones.

---

## 🧠 The 3D scene

| Element | What it does |
|---|---|
| Neural network | ~280 glowing nodes connected by lines, with data pulses travelling between them |
| Morphing shapes | Sphere → DNA helix → cube → torus → wave → galaxy, one per section |
| Core | Pulsing icosahedron with a wireframe shell and rotating HUD rings |
| Hologram grid | Custom GLSL shader floor with a scanning wave |
| Code panels | 8 floating panels showing snippets from the actual stack (Flask, MongoDB, RandomForest, Solidity…) |
| Data streams | Rising particle columns and background dust |

**Interactions:** cursor pushes and lights up nearby nodes · drag empty space to spin the network · click it for a shockwave · hover a code panel to bring it forward.

---

## 🎮 Interface features

- Boot-sequence loading screen
- Custom cursor with a reticle ring and click ripples
- Scroll-driven camera movement and network morphing
- Horizontally scrolling project section (pinned while you scroll down)
- 3D tilt cards with a cursor-following glow
- Scrambling headings, typing effect, 3D letter hover, animated counters
- Draggable skills sphere
- Flip cards for education and spinning certificate seals
- Live HUD readout: FPS, current section, network shape
- 4 accent themes: cyan, violet, amber, mint
- **Interactive terminal** — `whoami`, `skills`, `projects`, `experience`, `education`, `contact`, `hivetrust`, `theme <name>`, `morph <shape>`, `hack`, `clear`
- **Command palette** — `Ctrl` + `K`
- Hidden Matrix mode — `↑ ↑ ↓ ↓ ← → ← → B A`
- Respects `prefers-reduced-motion`, works with keyboard, and adapts to mobile

---

## 🛠 Built with

| Layer | Tech |
|---|---|
| 3D | Three.js (r128), custom GLSL vertex/fragment shaders |
| Frontend | HTML5, CSS3 (grid, custom properties, 3D transforms), vanilla JavaScript |
| Fonts | Chakra Petch, Manrope, JetBrains Mono (Google Fonts) |
| Deploy | GitHub Pages (any static host works) |

No frameworks, no bundler, no dependencies to install.

---

## 🚀 Run it locally

```bash
git clone https://github.com/aminul821/<repo-name>.git
cd <repo-name>
```

Then either open `index.html` in a browser, or serve it:

```bash
python -m http.server 8000
# open http://localhost:8000
```

### Deploy on GitHub Pages

1. Push the file as `index.html` to the `main` branch.
2. Go to **Settings → Pages**.
3. Set **Source** to `main` and folder `/ (root)`, then **Save**.
4. Your site goes live at `https://aminul821.github.io/<repo-name>/`.

---

## 🎨 Make it yours

| What to change | Where |
|---|---|
| Name, roles, about text | The `<section>` blocks in the HTML |
| Projects and details windows | The `PROJECTS` object in the script |
| Colors | The `THEMES` object and the `:root` CSS variables |
| Network size and shapes | `const N = …` and the `layouts` array |
| Terminal commands | The `C` object inside the terminal block |
| Code panels | The `SNIPS` array |

---

## 📦 Sections

`Home` · `About + terminal` · `Skills` · `Projects` · `Experience` · `Education, certifications & interests` · `Contact`

---

## 🐝 Featured project inside

**HiveTrust** — an AI + IoT + blockchain platform that verifies honey bottles and traces them back to the hive.
Built for **Smart India Hackathon 2026** (PS 26021, Agriculture · FoodTech & Rural Development) by **Team HexaDevelopers**.
Repo: [github.com/aminul821/hive](https://github.com/aminul821/hive)

---

## 📫 Contact

- **Email:** amansheyak1@gmail.com
- **GitHub:** [github.com/aminul821](https://github.com/aminul821)
- **LinkedIn:** _add your profile link_

---

## 📄 License

Released under the MIT License. Feel free to learn from the code — please replace my personal details with your own before publishing it as yours.
