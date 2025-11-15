# Images for CtrlStore

Place your product images inside the `images/` directory. The page expects three images per product named using this convention:

- `surface1-1.jpg`, `surface1-2.jpg`, `surface1-3.jpg`
- `surface2-1.jpg`, `surface2-2.jpg`, `surface2-3.jpg`
- ...
- `surface10-1.jpg`, `surface10-2.jpg`, `surface10-3.jpg`

If you only upload the `-1` image for each product, the thumbnail and modal will still work (the modal rotates across available images). Filenames are case-sensitive on most hosting platforms.

Quick upload steps (from repo root):

```bash
# add images into the images/ directory (copy or drag into workspace)
git add images/*.jpg
git commit -m "Add product images for CtrlStore"
git push origin main
```

Then open your GitHub Pages site or the `index.html` file to verify images load.

Notes:
- Use reasonably sized JPEGs (e.g. 1200×800) for good quality. Large images will slow page load.
- You can optimize images with tools like `jpegoptim` or an online compressor before uploading.

If you want, I can add sample placeholder images or run image-optimization commands—tell me which you'd prefer.
