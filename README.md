# toearthseed.org
This repository contains the website code for toearthseed.org. It uses github pages to build from the main branch. Templates use Jekyll, and maps are made with leaflet.js.

## local development
This website uses jekyll for its templating system
follow [these instructions](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll) to set up your computer to be able to run jekyll locally.

Then in the terminal:
* `cd path/to/toearthseed.org`
* `git pull origin main`
* `bundle exec jekyll serve`
* visit http://127.0.0.1:4000
* make your changes to the code
* `git add .`
* `git commit -m "describe what you did here"`
* `git push origin main` 
