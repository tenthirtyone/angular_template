# AngularJS Template

This is a small, modular, AngularJS template. It includes Bootstrap 3 and uses Bower for package management. Automation is setup with Gulp.

## Modular

The app is bisected into login/home submodules. Each is fully contained and includes Controller/Routing/SCSS/HTML/Service/Module files. To create a new submodule copy the 'home' folder and replace variable names.

For example, a directive example is contained in the home submodule.

### Installation

You need Gulp installed globally:

```sh
$ npm i -g gulp
```

```sh
$ git clone https://github.com/tenthirtyone/angular_template.git
$ cd angular_template
$ npm install && bower install
$ gulp
```

Gulp is configured to open Google Chrome automatically, if installed. Sometimes this feature is a bit buggy. Front end is dropped into ./build This can be changed by modifying the 'buildDir' variable in gulpfile.js. Drop that directory into /var/www/html for apache or serve with express / etc. 
