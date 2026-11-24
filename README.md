# Nguyễn Tài Anh — Portfolio

Personal portfolio of Nguyễn Tài Anh, Mobile & Web Developer (React Native · ReactJS · Laravel).
Static site — plain HTML, CSS and JavaScript, no build step.

## Structure

```
index.html              Portfolio (bilingual EN/VI, light/dark)
cv.html                 CV source (A4, printable)
cv/Nguyen-Tai-Anh-CV.pdf  Downloadable CV
assets/portrait.jpg     Portrait
assets/ivbbiz/          IVB Biz+ icon + official App Store screenshots
assets/cathay/          Cathay Insurance homepage screenshot
.nojekyll               Tells GitHub Pages to serve files as-is
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
# or
python3 -m http.server 8080
```

## Deploy to GitHub Pages

```bash
git init
git add .
git commit -m "Portfolio redesign"
git branch -M main
git remote add origin https://github.com/NguyenTaiAnh/<repo>.git
git push -u origin main
```

## Updating the CV

`cv.html` is the source. After editing it, re-export the PDF (open `cv.html` in Chrome → Print → Save as PDF, A4, margins: None, background graphics on) and replace `cv/Nguyen-Tai-Anh-CV.pdf`.

## Credits

App screenshots and icon © Indovina Bank (App Store listing); Cathay homepage © Cathay Insurance (Viet Nam). Sources in `assets/*/credits.json`.
# nguyentaianh.github.io
