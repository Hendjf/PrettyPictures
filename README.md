# PrettyPictures GitHub Pages Setup

A simple static image gallery for showcasing PNG flyers stored in this repository. This README explains how to preview locally and publish via GitHub Pages.

## Repository Structure

```
PrettyPictures/
├── index.html           # Gallery page (shown as “PrettyPictures Gallery” on GitHub)
├── Game_Night_1.png     # Flyer images (PNG format)
├── Town_Hall_Flyer.png
└── Weekly_Social_Flyer.png
```

## Local Preview

1. Clone the repository:

   ```bash
   git clone https://github.com/Hendjf/PrettyPictures.git
   cd PrettyPictures
   ```
2. Open the gallery page:

   * In your file explorer or terminal, open `index.html` in a web browser (double‑click or drag-and-drop).

## Publication with GitHub Pages

1. Ensure your changes are pushed to the **main** branch.
2. On GitHub, navigate to **Settings > Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Set:

   * **Branch**: `main`
   * **Folder**: `/` (root)
5. Click **Save**.
6. After a minute, your site will be live at:

   ```
   https://Hendjf.github.io/PrettyPictures/
   ```

## Updating the Gallery

* To add or remove images, place or delete `.png` files in the repo root.
* Edit the `images` array in `index.html` to match your filenames.

## Customization

* **Styling**: Adjust the CSS in `index.html` to modify layout, fonts, or colors.
* **Captions**: Change the `<figcaption>` text in the script section as needed.

---

Created by Hendjf • Powered by GitHub Pages
