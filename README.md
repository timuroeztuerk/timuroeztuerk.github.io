# timurozturk.de

Personal academic website for Timur Oeztuerk, built with Jekyll.

## Content

- `_pages/about.md` contains the landing page.
- `_pages/publications.html` renders research items from `_data/publications.yml`.
- `_pages/teaching.html` renders teaching items from `_data/teaching.yml`.
- `_pages/talks.html` renders talks from `_data/talks.yml`.
- `_pages/cv.md` embeds the current CV PDF.

## Local development

1. Install Ruby, Bundler, and Node.js.
2. Run `bundle install`.
3. Start the site with `bundle exec jekyll serve -l -H localhost`.

Open `http://localhost:4000` to preview the site.

## JavaScript bundle

If you change `assets/js/_main.js`, `assets/js/theme.js`, or `assets/js/plugins/jquery.greedy-navigation.js`, rebuild the bundled script:

```bash
npm install
npm run build:js
```
