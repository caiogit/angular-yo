# angular-yo

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.14.0.

Following the guide: [yo angular tutorial](http://yeoman.io/codelab/). [Currently at step 0]

Check this guide too: [Creating a useful AngularJS project structure and toolchain](http://manuel.kiessling.net/2014/06/09/creating-a-useful-angularjs-project-structure-and-toolchain/)

See [GitHub Yo Angular Generator page](https://github.com/yeoman/generator-angular) 

## PreBuild
```
mkdir my-new-project && cd $_
yo angular [app-name]

npm install -g grunt-cli bower yo generator-karma generator-angular

npm ls
? npm install phantomjs karma jasmine-core

sudo apt-get install ruby ruby-dev
sudo gem update --system
sudo gem install compass

grunt

cd node_modules/grunt-contrib-imagemin/
npm install imagemin@4.0.0
cd -
```

## Build & development

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.

## Link

- [Angular Fiddles](https://github.com/angular/angular.js/wiki/JSFiddle-Examples)
 - [Dynamic Forms](http://jsfiddle.net/buele/nYzjY/)
 - [Table with limit and pagination](http://jsfiddle.net/SAWsA/11/)
- [RESTful services Quick Tips](http://www.restapitutorial.com/lessons/restquicktips.html)
- [Miredot: JSON API automatic documentation](http://www.miredot.com/exampledocs/#-300843329)
