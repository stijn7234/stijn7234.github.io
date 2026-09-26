# Stijn Bier Portfolio

Simple static portfolio website built with HTML, CSS and a small amount of JavaScript.

## Run locally
Open `index.html` in your browser.

## Publish with GitHub Pages
1. Create a new GitHub repository, for example `stijn7234.github.io`.
2. Upload all files in this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save. Your site will be available at `https://stijn7234.github.io/`.

## Add images
Put images in `assets/images/`.

Example on a project page:
```html
<img src="../assets/images/thesis-handtrainer.jpg" alt="Hand trainer with camera tracking markers">
```

## Add video
Put small web-friendly videos in `assets/videos/`.

Example:
```html
<video autoplay muted loop playsinline controls>
  <source src="../assets/videos/beachbot-demo.mp4" type="video/mp4">
</video>
```

For larger videos, embed an unlisted YouTube video instead.

## Suggested next steps
- Replace the `SB` avatar with a portrait.
- Add one strong hero image for every project.
- Add 3–6 supporting visuals per project.
- Add measurable results to the thesis page.
- Add GitHub links only for repositories that are clean enough to show.
- Add a CV download button once the final CV filename is known.
