# angular-yo

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.14.0.

Following the guide [yo angular tutorial](http://yeoman.io/codelab/). [Currently at step 0]

See [GitHub page](https://github.com/yeoman/generator-angular) 

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
