# ReverbRVA

Site published at [ReverbRVA.com](http://www.ReverbRVA.com) using GitHub Pages. 

## GitHub Pages formatting

### Pages
All pages are published using the base name (no .md!) in the directory where they are placed. So in the case of `about.md`:

- If placed in the repo root, it would be published as [ReverbRVA.com/about](ReverbRVA.com/about)
- If placed in the `northside` directory, it would be published as [ReverbRva.com/northside/about](ReverbRva.com/northside/about
)

### Titles

If you would like to customize the title on any page, add the following YAML front matter:
```yaml
---
title: "{{ Page Title }}"
---
```
Repace {{ Title }} with a title of your choice.

### Additional Documentation

- Documentation for GitHub pages can be found at [GitHub pages help](https://help.github.com/categories/github-pages-basics/)
- This page is built using the built-in theme from GitHub called [Tactile](https://github.com/pages-themes/tactile)
