# angular-yo

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.14.0.

Following the guide: [yo angular tutorial](http://yeoman.io/codelab/). [Currently at step 6]

Check this guide too: [Creating a useful AngularJS project structure and toolchain](http://manuel.kiessling.net/2014/06/09/creating-a-useful-angularjs-project-structure-and-toolchain/)

See [GitHub Yo Angular Generator page](https://github.com/yeoman/generator-angular) 

## PreBuild
```
[
sudo apt-get install ruby ruby-dev
yum install ruby ruby-devel
]

sudo npm install -g npm
sudo npm install -g grunt-cli bower yo generator-karma generator-angular

sudo npm cache clean -f
sudo npm install -g n
sudo n stable

sudo gem update --system
sudo gem install compass

node --version && npm --version && bower --version && grunt --version && git --version && compass --version && yo --version
yo doctor

mkdir my-new-project && cd $_
yo angular [app-name]

npm ls
npm install
? npm install phantomjs
? npm install jasmine-core
? npm install karma


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

## Pacchetti interessanti Javascript (with Bower)

- [15 useful AngularJS Tools](http://www.hongkiat.com/blog/angularjs-tools/)

- Angular Translation
 - [Angular gettext](https://angular-gettext.rocketeer.be/)
 - [Angular Translate](https://github.com/angular-translate/angular-translate)
- [JQuery Validation](https://github.com/jzaefferer/jquery-validation)
- [AngularJS Validation] (https://github.com/angular-ui/ui-validate)
- [JQuery Select2](https://github.com/select2/select2) (ricercare select2 per angular)
 - [Select2 / Bootstrap Integration](https://github.com/t0m/select2-bootstrap-css)
- [JQuery Validation](https://github.com/jzaefferer/jquery-validation)
- [Angular Local Storage](https://github.com/grevory/angular-local-storage): For using browser local storage
- [Angular Bootsrap](https://github.com/angular-ui/bootstrap) Native AngularJS implementation of Bootstrap JS libs
- [Angularitics](https://github.com/angulartics/angulartics): Analytics for AngularJS
- [LoDash (_)](https://lodash.com/): Tools set for JS
- [MomentJS](momentjs.com): Tools for date manipulation
- [Typeahead](twitter.github.io/typeahead.js): Twitter library for google instant search clone
- Chrome Extensions:
 - [Angular Batarang](https://github.com/angular/batarang)
 - [ng-inspector](http://ng-inspector.org/)
- REST:
 - [RestAngular](https://github.com/mgonto/restangular)

