# grunt-buddha-suncg

> buddha bless me

## Getting Started
This plugin requires Grunt.

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-buddha-suncg --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-buddha-suncg');
```

## The "buddha" task

### Overview
In your project's Gruntfile, add a section named `buddha` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  buddha: {
    options: {
      // Task-specific options go here.
    },
    your_target: {
      // Target-specific file lists and/or options go here.
    },
  },
})
```

### Options

#### options.who
Type: `String`
Default value: `'buddha'`


指明是用佛祖还是神兽来保佑代码

#### options.commentSymbol
Type: `String`
Default value: `'//'`

文件中拼接佛祖或神兽时使用的注释符

### Usage Examples

#### Default Options

```js
grunt.initConfig({
  buddha: {
    options: {
    'who':'buddha',
    'commentSymbol':'//'
    },
   dist:['example/*.js']
  },
})
```



## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).


## Release History
> 2015-11-18 test

> 2015-10-23 v0.0.3 README.MD change by [suncg](http://www.sunchenguang.com/)

> 2015-10-7 v0.0.2 optimization

> 2015-4-12 v0.0.1 init

## License
Copyright (c) 2015 suncg. Licensed under the MIT license.
