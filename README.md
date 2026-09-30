# Mock-UP — Store Screenshot Builder

A lightweight, browser-based tool for creating **App Store** and **Google Play** marketing screenshots — with device frames, titles, brand footer, and 3D stacked emoji icons — exported as **opaque PNGs** at official store dimensions.

Built for product teams, indie developers, and marketers who need polished store creatives without opening Figma or Photoshop.

<img width="887" height="974" alt="Screenshot 2026-09-30 at 8 41 54 pm" src="https://github.com/user-attachments/assets/c9cac233-1906-4d30-8f17-aa292ab26152" />
<img width="929" height="963" alt="Screenshot 2026-09-30 at 8 42 26 pm" src="https://github.com/user-attachments/assets/a8e8d3c2-b1fa-41f3-beb5-a9542390f727" />
---

## Features

- **Phone & tablet frames** with portrait / landscape layouts
- **Store-ready export sizes** for Apple App Store and Google Play
- **Ready-made templates** (tasks, departments, dashboard, login, blank)
- **Custom title, subtitle, colors, and footer branding**
- **3D stacked emoji icons** with dropdown picker + free-text / paste support
- **Arabic & English UI** (RTL / LTR)
- **Light & dark mode**
- **Screenshot upload** into a realistic device frame
- **Opaque PNG export** (no alpha / transparency — store-safe)

---

## Supported export sizes

### Apple App Store
| Device | Orientation | Size |
|--------|-------------|------|
| iPhone 6.5" | Portrait | 1242 × 2688 |
| iPhone 6.5" | Landscape | 2688 × 1242 |
| iPhone 6.7" | Portrait | 1284 × 2778 |
| iPhone 6.7" | Landscape | 2778 × 1284 |
| iPad 12.9" | Portrait | 2048 × 2732 |
| iPad 12.9" | Landscape | 2732 × 2048 |

### Google Play
| Device | Orientation | Size |
|--------|-------------|------|
| Phone | Portrait | 1080 × 1920 |
| Phone tall | Portrait | 1080 × 2340 |
| Tablet | Portrait | 1600 × 2560 |
| Tablet | Landscape | 1920 × 1200 |

---

## Quick start

1. Clone the repository:

```bash
git clone git@github.com:Youssef-Khorshed/Mock-UP.git
cd Mock-UP
```

2. Open `mockup.html` in any modern browser  
   (Chrome, Edge, Safari, or Firefox — double-click the file or drag it into a tab).

3. Customize copy, colors, icons, and device type.

4. Upload your app screenshot.

5. Click **Download store-size PNG**.

No build step. No Node. No install.

---

## How to use

1. Choose **device type** (phone / tablet) and **orientation**.
2. Pick an **export size** that matches the store listing you need.
3. Select a **template** or write your own title and subtitle.
4. Adjust background colors and footer brand text.
5. Set the four stacked icons via the emoji dropdown or by typing/pasting.
6. Upload a screenshot — it appears inside the device frame.
7. Export the final PNG at the selected store resolution.

---

## Project structure

```
Mock-UP/
├── mockup.html   # Full single-file app (UI + logic + export)
└── README.md
```

Everything runs from one HTML file for easy sharing and hosting.

---

## Tech notes

- Pure HTML / CSS / JavaScript
- Client-side export via [html2canvas](https://html2canvas.hertzen.com/)
- PNG output is flattened to opaque RGB (no alpha channel) for App Store / Play Store compliance
- Language and theme preferences are saved in `localStorage`

---

## License

MIT — free to use, modify, and share.

---

## Author

**Youssef Khorshed**  
GitHub: [Youssef-Khorshed](https://github.com/Youssef-Khorshed)
