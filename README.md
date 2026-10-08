# Daniel Sandoval Resume

This repository contains the source code for Daniel Sandoval's professional resume website. The site is designed to showcase experience, skills, and education in a clean, accessible, and responsive format.

## Purpose

The purpose of this repository is to provide an online, interactive, and easily updatable resume for Daniel Sandoval. It demonstrates professional experience, technical skills, and project management capabilities.

## Technologies Used

- **HTML5** and **CSS3** for structure and styling
- **SVG** for custom icons
- **Font Awesome** for social and document icons
- **Google Fonts** for typography
- **JavaScript** for dark mode toggle and interactivity

## Regenerating the PDF

`assets/DanielSandoval.pdf` is printed from `index.html` (layout comes from the `@media print` rules in `styles.css`). After editing the HTML, run from the repo root:

```sh
google-chrome --headless --no-pdf-header-footer --virtual-time-budget=5000 \
  --print-to-pdf="$PWD/assets/DanielSandoval.pdf" "file://$PWD/index.html"
```

## License

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).

You are free to:

- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material

**Under the following terms:**

- **Attribution** — You must give appropriate credit.
- **NonCommercial** — You may not use the material for commercial purposes.

See the [LICENSE](https://creativecommons.org/licenses/by-nc/4.0/) for full license terms