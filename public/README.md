# Markdown Resume Builder

## Create a github pages user page

- make a new github repo
- repo's name MUST be `yourusername.github.io`
- `cd yourusername.github.io`
- touch index.html
- mkdir css
- touch css/main.css
- git add --all
- git commit
- git push -u origin master

## Use the markdown resume builder

- fork and clone this repo
- run `gulp`
- create your resume in the app/index.md file using ONLY markdown
- some default styles are already pre-loaded. if you'd like to override any defaults with your own custom styling, add your styles to app/scss/styles.scss

## Add your resume to your github.io page

- copy the public/index.html file from your resume builder
- paste it into the index.html file in your `yourusername.github.io` directory
- copy the public/styles.css file from your resume builder
- paste it into the `css/main.css` file in your `yourusername.github.io` directory
