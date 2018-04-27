# Get started quick and easy with Hugo and Sass

A [Hugo](https://gohugo.io/) starter project using [Sass](https://sass-lang.com/) utilising [gulp](https://gulpjs.com/) workflow.

Inspired by [@dan_bahrami](https://twitter.com/dan_bahrami)'s [article](http://danbahrami.io/articles/building-a-production-website-with-hugo-and-gulp-js/) about gulp setup for using sass in a Hugo project.

## What you get
* Simple Hugo project with a list view and two single pages without theme
* Gulptask for watching sass
* Gulptask for building production site
* A buildscript that builds Hugo and sass
    * Super easy to deploy, for example on [Netlify](https://www.netlify.com/)

Note: In this project `static` is dynamically generated from `src` and added to `gitignore`.

## How to use
Requires hugo. Install instructions [here](https://gohugo.io/getting-started/quick-start/).

In some cases gulp needs to be installed globally before proceeding. In that case run: `npm install -g gulp`.

### Development
From the project directory on you machine:
1. Install depencencies: `npm install`
2. Start live reload server: `hugo server -wvD`
3. Start Sass watcher: `gulp watch`
4. **Happy coding**
### Production
`npm run build`

Demo deployed here: [hugo-sass-starter.netlify.com](https://hugo-sass-starter.netlify.com/)
## Acknowledgements

Thanks to [@dan_bahrami](https://twitter.com/dan_bahrami) for the inspiration.

Thanks also to [@pappapez](https://twitter.com/pappapez) for help with writing the build-script and the gulpfile and everything else!

## Feedback welcome

* File an issue on GitHub
* Or tweet me [@martinlainen](https://twitter.com/martinlainen)
