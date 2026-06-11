# personal website

A super simple, web 1.0 style site. Just HTML files, one stylesheet, Times New Roman.

## structure

```
index.html                      home (writings / projects / curriculum vitae)
writings.html                   list of writings
writings/on-universities.html   a writing
writings/on-truth.html          a writing
writings/on-ai.html             a writing
projects.html                   projects (tuva, kthais, artemis)
cv.html                         download my cv
cv.pdf                          the cv file (placeholder - replace it)
style.css                       all the styling
images/                         project images go here
```

## editing

- **Write a post:** open the `writings/*.html` file and replace the `<p>` text.
  Use `<h2>...</h2>` for sub-headings inside a post.
- **Add a writing:** copy an existing file in `writings/`, then add a link to it
  in `writings.html`.
- **Add a project image:** drop the file in `images/`, then in `projects.html`
  replace the `<div class="placeholder">...</div>` with `<img src="images/yourfile.png" alt="...">`.
- **Replace the CV:** overwrite `cv.pdf` with your real CV (keep the filename).
- **Colors / spacing / font:** everything lives in `style.css`.

## hosting on github pages

1. Push this repo to GitHub.
2. Go to the repo's **Settings -> Pages**.
3. Under **Build and deployment**, set **Source: Deploy from a branch**,
   **Branch: main**, **Folder: / (root)**. Save.
4. After a minute the site is live at
   `https://<your-username>.github.io/<repo-name>/`.

To use a custom domain, add it under Settings -> Pages and create a `CNAME` file.
