# grunt-buddha-xiaofang

> xiaofang buddha

## Getting Started
This plugin requires Grunt.

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-buddha-xiaofang --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-buddha-xiaofang');
```

## The "buddha_xiaofang" task

### Overview
In your project's Gruntfile, add a section named `buddha_xiaofang` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  buddha_xiaofang: {
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
Default value: `buddha`

佛祖保佑还是神兽保佑

A string value that is used to do something with whatever.

#### options.commentSymbol
Type: `String`
Default value: `//`
文件中的注释

A string value that is used to do something else with whatever else.

### Usage Examples

#### Default Options
In this example, the default options are used to do something with whatever. So if the `testing` file has the content `Testing` and the `123` file had the content `1 2 3`, the generated result would be `Testing, 1 2 3.`

```js
grunt.initConfig({
  buddha_xiaofang: {
     options: {
        who: 'buddha',   // buddha alpaca
        commentSymbol: '//'
      },
      dist: ['test/fixtures/*.js']
  },
})
```



## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).

## Release History
2015-11-2 &nbsp;&nbsp;&nbsp;&nbsp; init

## License
Copyright (c) 2015 xiaofangmoon. Licensed under the MIT license.
