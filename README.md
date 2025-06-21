# PrettyPictures GitHub Pages Setup

A simple static image gallery for showcasing PNG flyers stored in the repository. This README explains how to preview locally and publish via GitHub Pages.

## Repository Structure

```
PrettyPictures/
├── docs/
│   ├── index.html    # Gallery page
│   ├── Game_Night_1.png
│   ├── Town_Hall_Flyer.png
│   └── Weekly_Social_Flyer.png
└── README.md          # This file
```

## Local Preview

1. Clone the repo:

   ```bash
   ```

git clone [https://github.com/Hendjf/PrettyPictures.git](https://github.com/Hendjf/PrettyPictures.git)
cd PrettyPictures

```
2. Open the gallery in your browser:
   - Navigate to `docs/index.html` and open it (double‑click or drag into a browser).
   - You should see all three flyers displayed in a responsive grid.

## Publishing with GitHub Pages
1. Push your changes to the **main** branch (or default branch).
2. In the GitHub repo, go to **Settings > Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose:
   - **Branch**: `main`
   - **Folder**: `/docs`
5. Click **Save**.
6. After a minute, your site will be live at:
```

[https://Hendjf.github.io/PrettyPictures/](https://Hendjf.github.io/PrettyPictures/)

```

## Updating the Gallery
- To add or remove images, place or delete the PNG files in the `docs/` folder, then commit and push.
- The `<script>` in `index.html` automatically references the three filenames listed in the `images` array. Edit that array to match your file names.

## Customization
- **Layout**: Modify the CSS in `docs/index.html` to change grid settings, margins, or typography.
- **Captions**: Change the `figcaption` text in the script section.

---
Created by Hendjf • Powered by GitHub Pages

```
