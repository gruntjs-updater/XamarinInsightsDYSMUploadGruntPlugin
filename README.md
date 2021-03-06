# grunt-xamarininsightsdysmupload

> Quick way to zip and upload your iOS DYSM to Xamarin Insights

Inspired by a [blog post](http://thetechnologystudio.co.uk/blog/) and [gist](https://gist.github.com/robert-waggott/528238a7fb2893db97fd).

## Getting Started
This plugin requires Grunt `~0.4.5`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-xamarininsightsdysmupload --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-xamarininsightsdysmupload');
```

## The "XamarinInsightsDYSMUpload" task

### Overview
In your project's Gruntfile, add a section named `XamarinInsightsDYSMUpload` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  XamarinInsightsDYSMUpload: {
    dysm: "",
    apiKey: "abc"
  }
});
```

### Options

#### apiKey
* Type: `String`
* Default value: `''`

Your Xamarin Insights API key. 

#### dysm
* Type: `String`
* Default value: `''`

The path to your dysm. 

### Usage Examples

```js
grunt.initConfig({
  XamarinInsightsDYSMUpload: {
    dysm: "/foo/bar/abc.dYSM",
    apiKey: "abc"
  }
});
```
