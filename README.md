# phantomjs-polyfill-object-assign

Object.prototype.assign polyfill for phantom.js based on https://github.com/tom-james-watson/phantomjs-polyfill and
https://github.com/ptim/phantomjs-polyfill-find

This is a polyfill for Object.prototype.assign which is missing from PhantomJS.


## Installation

```
    npm install --save-dev phantomjs-polyfill-object-assign
```

## Usage with Karma

Include the polyfill directly in the files list of your karma.conf

```
    ...
    files: [
      './node_modules/phantomjs-polyfill-object-assign/object-assign-polyfill.js',
      ...
    ]
    ...
```
