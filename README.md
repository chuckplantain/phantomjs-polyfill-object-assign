# phantomjs-polyfill-find

Array.prototype.find polyfill for phantom.js based on https://github.com/tom-james-watson/phantomjs-polyfill

This is a polyfill for Array.prototype.find which is missing from PhantomJS.


## Installation

```
    npm install --save-dev ptim/phantomjs-polyfill-find
```


## Usage

```
    require('phantomjs-polyfill')
```


## Usage with Karma

Include the polyfill directly in the files list of your karma.conf

```
    ...
    files: [
      './node_modules/phantomjs-polyfill-find/find-polyfill.js',
      ...
    ]
    ...
```
