The project was built assuming it is hosted at the server root. To override this, specify the homepage in your package.json. For example, add this to build it for GitHub Pages:

"homepage" : "http://myname.github.io/myapp",

The bookshelf_build folder is ready to be deployed. You may serve it with a static server:

npm install -g serve

serve -s bookshelf_build
