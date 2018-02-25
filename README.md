# AzizAli.com

## Backstory
For the longest time I have been a fan of Wordpress, but the development lifcycle is drag and the slow speed of the server discourages me from authoring on Wordpress. So finally I entertained the idea of moving away.

Jekyll came to mind since one of my very respectable co-worker was hosting his personal website with Jekyll

## Technology used
- [Jekyll](https://jekyllrb.com/) to build the static pages
- [Disqus](https://disqus.com/) for comments
- [exitwp](https://github.com/thomasf/exitwp) to transfer wordpress posts to jekyll
- [wordpress-comments-jekyll-staticman](https://www.npmjs.com/package/wordpress-comments-jekyll-staticman) to transfer wordpress comments to staticman
- Github Pages to host the website

## To run the project
- `bundle install --path vendor/bundle`
- `npm install yarn -g`
- `yarn install`
- `npm start`

## Todo
- [X] Replace Staticman with disqus comments
- [X] Meta data
- [X] Figure out how to add Title to the page
- [X] add now page
- [ ] Add Favicon