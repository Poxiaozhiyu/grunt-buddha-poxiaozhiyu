# grunt-buddha-poxiaozhiyu

> Buddha's grace illuminates code as sunshine.

## Where is it from?
[grunt-buddha](https://github.com/materliu/grunt-buddha)

[materliu](https://github.com/materliu)

## Getting Started
This plugin requires Grunt `~0.4.5`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-buddha-poxiaozhiyu --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-buddha-poxiaozhiyu');
```

## The "buddha_poxiaozhiyu" task

### Overview
In your project's Gruntfile, add a section named `buddha_poxiaozhiyu` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  buddha_poxiaozhiyu: {
    options: {
      // Task-specific options go here.
    },
    your_target: {
      // Target-specific file lists and/or options go here.
    },
  },
});
```

### Options

#### options.who
Type: `String`
Default value: `buddha`

指明是佛祖(buddha)还是神兽(alpaca)来保佑我们的代码。

#### options.commentSymbol
Type: `String`
Default value: `//`

文件中拼接佛祖或神兽时使用的注释符。

### Usage Examples

#### Default Options
In this example, the default options are used to do something with whatever. So if the `testing` file has the content `Testing` and the `123` file had the content `1 2 3`, the generated result would be `Testing, 1 2 3.`

```js
grunt.initConfig({
  buddha_poxiaozhiyu: {
    options: {
        who: 'alpaca',
        commentSymbol: '//'
    },
    dist: ['examples/*.js'],
  },
});
```


## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).

## Release History
2017-09-24&npsp;&npsp;&npsp;v0.1.0&npsp;&npsp;&npsp;init
