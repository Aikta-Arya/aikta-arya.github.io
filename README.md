# Aikta Arya — Academic Website

Static multi-page academic website. All pages, styles, scripts, and assets are kept in this folder.

## Deploy to GitHub Pages

1. Upload the **contents** of this folder to the root of the GitHub Pages repository (the HTML files should sit beside `styles.css`).
2. In GitHub, open **Settings → Pages** and select the intended branch and `/ (root)` folder.
3. Wait for the Pages deployment to finish, then open the published URL in a fresh tab.
4. If the browser still shows an older layout, hard-refresh once (`Ctrl+Shift+R` on Windows/Linux). The stylesheet URL includes a version query so browsers/CDNs request the current CSS after this update.

The site uses relative `./` paths, so it works both at a user-site URL (`username.github.io`) and a project-site URL (`username.github.io/repository/`), provided the folder contents are deployed at the selected Pages publishing root.

## Required assets

- `assets/profile-photo.jpg`
- `assets/Aikta_Arya_CV.pdf`

Do not rename these files unless the corresponding HTML references are updated as well.
