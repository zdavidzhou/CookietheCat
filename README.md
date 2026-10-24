# Cookie the Cat 🐾

A personal website for Cookie, a 5-year-old Ragdoll cat.

## Publish on GitHub Pages
1. Create a **public** GitHub repository named `cookie-the-cat`.
2. Upload `index.html` and `CNAME` to the top level of that repository (README.md is optional).
3. Go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, **main** and **/(root)**, then save.
4. In **Settings → Pages → Custom domain**, confirm `cookiethecat.online` and save.
5. In Namecheap **Advanced DNS**, set four GitHub Pages A records for `@` and `www` CNAME to `YOUR-USERNAME.github.io` (replace the username).
6. When DNS/certificate is ready, enable **Enforce HTTPS** in GitHub Pages.

## Customize photos
Replace the `<span class="placeholder">...</span>` sections inside `#gallery` in `index.html` with image tags like `<img src="photos/cookie-1.jpg" alt="Cookie relaxing" loading="lazy">`. Put real photos in a `photos/` folder and commit them.

This starter website requires no build step, dependencies, or paid hosting.
