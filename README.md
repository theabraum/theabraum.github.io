# theabraum.com

Thea Braum's website, built with [Hugo](https://gohugo.io) and published to GitHub Pages at https://www.theabraum.com.

## Quick edits (in the browser)

- **Rates, who I teach, location, booking text:** `data/lessons.yaml`
- **About me paragraph, tagline:** `content/_index.md`
- **Photo:** replace `assets/images/thea.jpg`

Open the file on GitHub, click the pencil icon, edit, then **Commit changes**. The site rebuilds automatically in about a minute (see the **Actions** tab).

## Run locally

```
hugo server
```

Then open http://localhost:1313.

## Layout

- `layouts/baseof.html`: page shell (head, header, footer)
- `layouts/home.html`: the lessons home page
- `layouts/_partials/`: header and footer
- `assets/css/main.css`: all styles
- `hugo.toml`: site settings and the navigation menu (Art and Resume are ready to uncomment)
