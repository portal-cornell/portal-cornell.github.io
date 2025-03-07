# People and Robots Teaching and Learning (PoRTaL) group website 

Soruce code for the PoRTaL website: https://portal.cs.cornell.edu/

The website is based off of the alfolio Jekyll theme (https://github.com/alshedivat/al-folio). 

## Updating the website

Updating the website is easy. Make sure you are on the `main` branch, make your changes, commit and push. Note that `bundle exec jekyll serve --incremental` sometimes does not show the updated news. To view the website locally

``` bash
bundle exec jekyll serve
```

When you are ready to deploy the website, type:

``` bash
./bin/deploy
```

The script builds the html pages and pushes to the `gh-pages` branch which is hosted as a github page.
