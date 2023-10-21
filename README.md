# patrix-portfolio-website

Portfolio website written with Bootstrap &amp; SASS

Following tutorial on freeCodeCam.org's YouTube channel
Tutorial URL: https://youtu.be/iJKCj8uAHz8

Technologies used:

- HTML
- CSS
- Sass
- Bootstrap

Notes to self:

1. Create a repository
2. Initiate npm - in terminal write: npm init - package.json file will be created
3. Install SASS package - in terminal write: npm install --save-dev sass - node_modules folder will appear, SASS dependency will be mentioned in package.json file
4. Install bootstrap package - in terminal write: npm install bootstrap --save - bootstrap dependency will be added to package.json file

- Additional steps:

5. Install Font Awesome package - in terminal write: npm install --save @fortawesome/fontawesome-free
6. Install autoprefixer - in terminal write: npm install postcss-cli autoprefixer --save
7. Doublecheck if all dependencies are in the package.json file
8. Install glightbox for displaying youtube video - download source files from https://biati-digital.github.io/glightbox/, unzip and copy dist/css and dist/js folders to your assets

Creating npm script to compile sass to css:

1. In package.json file, under "Scripts" remove any default script and replace it with the following: "compile:sass": "sass --watch scss:assets/css"
2. Create scss folder and style.scss file inside
3. Start compiling by running sass compiler with npm by writing the following in terminal: npm run compile:sass
4. assets/css folders will be created and within them style.css and style.css.map files

Notes from other tutorials:

1. Create a .gitignore file to ingore unnecessary files being uploaded to a girhub repo
2. Inside the .gitignore file write the following: node_modules
