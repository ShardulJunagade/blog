# Shardul's Quarto Blog

This is the source repository for [shardul's blog](https://sharduljunagade.github.io/blog/), built with [Quarto](https://quarto.org/).

## Features
- Blog posts with categories, filters, and RSS feed
- Custom themes and styles
- About page with social links
- Comments via Giscus

## Getting Started

### Prerequisites
- [Quarto](https://quarto.org/docs/get-started/) (install from the official site)
- [Pandoc](https://pandoc.org/) (automatically included with Quarto)

### Running Locally
1. Open a terminal in this directory.
2. Run:
   ```
   quarto preview
   ```
3. Open the local URL shown in the terminal (usually http://localhost:4200) to view the blog.

### Building the Site
To build the static site (output to the `_site/` folder):
```
quarto render
```

### Publishing
To publish to GitHub Pages or another static host, see the [Quarto publishing guide](https://quarto.org/docs/publishing/).

## Directory Structure
- `_quarto.yml` — Main Quarto configuration
- `index.qmd` — Blog index page
- `about.qmd` — About page
- `posts/` — Blog posts (each in its own folder)
- `styles.css`, `theme-light.scss`, `theme-dark.scss` — Custom styles

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


