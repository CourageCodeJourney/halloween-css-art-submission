
## 🕸️halloween-css-art-submission
Pure CSS Halloween Art — a haunted night scene built entirely with HTML and CSS animations.

### 📂 Project Structure

```
halloween-css-art/
│
├── index.html        # Main HTML file that loads the CSS and displays the scene
└── halloween.css     # All the styling and animations (core of the art)
```

---

### 🧱 File Breakdown

#### **index.html**

* Contains the root structure of the Halloween scene.
* Each `<div>` represents an object or animated element in the scene — e.g.

  * `.blood-moon` → glowing red moon
  * `.haunted-house` → central building with windows and doors
  * `.spider`, `.ghost`, `.pumpkin`, `.skeleton`, etc. → animated elements
* The file only references one stylesheet:

  ```html
  <link rel="stylesheet" href="halloween.css" />
  ```

#### **halloween.css**

* Defines **all visual elements and animations** for the scene.
* Key techniques:

  * **Positioning:** Absolute layout to place each object precisely
  * **Gradients:** Used to paint every shape (no images used)
  * **Animations:** Controlled via `@keyframes` for motion effects
  * **Pseudo-elements:** (`::before`, `::after`) to add layered detail without extra HTML
* Organized into sections (for readability):

  ```css
  /* Glitch Horror Effect */
  /* Sky */
  /* Blood Moon */
  /* Screaming Faces */
  /* Lightning */
  /* Spiders */
  /* Haunted House */
  /* Trees */
  /* Pumpkins */
  /* Ghosts */
  /* Skeletons */
  /* Graveyard */
  /* Fog & Shadows */
  /* Responsive */
  ```

---

### ⚙️ How to Run Locally

1. **Open the folder** containing your files.
2. Double-click on `index.html` — it will open in your default browser.

   * No setup, dependencies, or build tools are required.
3. For a better fullscreen view:

   * Press `F11` (on Windows) or `Ctrl + Cmd + F` (on Mac).
   * Make sure browser zoom is 100%.

---

### 🧪 Troubleshooting

| Issue                                | Cause                       | Fix                                                   |
| ------------------------------------ | --------------------------- | ----------------------------------------------------- |
| Horizontal scrollbar appears         | CSS used `100vw` width      | Already fixed with `overflow:hidden` and `width:100%` |
| Scene looks cropped on small screens | Limited viewport height     | Resize browser or test on larger device               |
| Animations lag                       | Heavy CSS shadows and blurs | Close other tabs or disable “energy saver” mode       |

---

### 🧰 Dependencies

None — this is **pure HTML + CSS**.
No frameworks, JS libraries, or build steps required.

---
