# Vision Intelligence Lab

Source code for the Vision Intelligence Lab website at
[danli-vision.github.io](https://danli-vision.github.io).

## Project structure

- `_pages/about.md`: homepage content
- `_config.yml`: site and author settings
- `_data/navigation.yml`: navigation links
- `_includes/` and `_layouts/`: page templates
- `assets/css/main.scss` and `_sass/`: site styles
- `assets/js/main.min.js`: browser-side theme bundle
- `images/`: profile image, contact image, and site icons

## Local development

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve --livereload
```

The local site is available at <http://127.0.0.1:4000>.

The production site is deployed by GitHub Pages from the `main` branch.

## Credits

Built with Jekyll and adapted from AcadHomepage and Minimal Mistakes. See
`LICENSE` for licensing information.
