## Clean HTML only and GruntJS based project scaffold

Clean without any frontend frameworks
With Node Scss workflow, Normalize.css and jQuery

### Features

- node-sass
- cssmin
- uglify
- concat
- jshint
- wiredep (bower install)
- imagemin
- server with livereload

### Start

You need git, bower, npm

````
git clone git@github.com:juliancwirko/html-project.git
cd html-project
npm install
bower install
````

### Tasks

Watch 127.0.0.1:9000 with livereload
````
grunt
````

Publish dist folder
````
grunt publish
````

Watch 127.0.0.1:9001 only preview from dist folder
````
grunt server-dist
````

If you need Front-End framework you should check out [Yeoman generator for Zurb Foundation 5](https://github.com/juliancwirko/generator-zf5)
