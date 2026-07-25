# Product Design Collection

Static GitHub Pages bundle containing all project demos and the NOVA React build.

## Publish

Create an empty GitHub repository, then run these commands from this folder:

```bash
git init
git add .
git commit -m "Publish product design collection"
git branch -M main
git remote add origin https://github.com/Aisoexe1/product-design-collection.git
git push -u origin main
```

In GitHub repository settings, open **Pages** and choose **GitHub Actions** as the source. The included workflow publishes automatically after each push.

The site will be available at:

`https://aisoexe1.github.io/product-design-collection/`
