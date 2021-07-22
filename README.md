## My Personal Website
It is built with the static site generator [Hugo](https://gohugo.io/).

It is hosted on github pages and served from the [gh-pages](https://github.com/joejean/joejean.github.io/tree/gh-pages) branch of this repo.

### Publishing workflow
1- Make sure Hugo [is installed](https://gohugo.io/getting-started/installing/) on the computer

2- Create a new branch

2- Add the new post/page, or update existing one.

3- Run `hugo server -D` to test the changes locally http://localhost:1313/

4- Push the changes, open a PR and merge it

5- Once the PR is merged to master, the [Github Actions](https://github.com/joejean/joejean.github.io/actions) workflow should publish the new version of the site to the `gh-pages` branch
