# [wlp2022.dfki.de](https://wlp2022.dfki.de)

Source files of the conference website for the _36th Workshop on (Constraint) Logic Programming_ (WLP), [wlp2022.dfki.de](https://wlp2022.dfki.de).

The design is based on the [_Event_ Template from _themeforest_](https://themeforest.net/item/event-conference-event-html5-landing-page/10050747).

## Build

The website is automatically built and deployed to GitHub Pages. For local development, you need [jekyll](https://jekyllrb.com/docs/). Then, run the following commands:

```sh
bundle install
bundle exec jekyll serve --livereload # runs at http://localhost:4000/
bundle exec jekyll build # alternatively, built into the `_site` directory
```
