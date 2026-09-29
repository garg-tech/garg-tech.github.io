# garg-tech.github.io

Source for [garg-tech.github.io](https://garg-tech.github.io), the personal research site of Devansh Garg.

Plain HTML and one CSS file. No build step, no framework, no dependencies. Push to `main` and GitHub Pages serves it.

To preview locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

`/cv/index.html` mirrors the LaTeX CV. When one changes, update the other and replace `assets/Devansh_Garg_CV.pdf` in the same commit.
