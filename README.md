# Multilingual and Multimodal LLMs in the Wild — Tutorial Site

This repository hosts the static Jekyll site for the tutorial. The GitHub Pages URL is `http://mm-llms-in-the-wild.github.io`.

## Local development
1. Install Ruby and Bundler.
2. Install gems: `bundle install`
3. Serve locally: `bundle exec jekyll serve`

## Deployment
Pushes to `main` trigger the GitHub Actions workflow (`.github/workflows/main.yml`) that builds the site and publishes it to the `gh-pages` branch.
