# How to upload vite-react to Github-pages

npm create vite@latest

npm install

publish 

vite.config.js > base: '/repo/',

npm install gh-pages --save-dev

"homepage": "https://github.com/KTkodehode/pages-test", (package.json > top)

package.json(scripts) > predeploy: "npm run build", deploy: "gh-pages -d dist"

commit

npm run deploy


https://ktkodehode.github.io/pages-test/
