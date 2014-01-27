# Small collection of mixins and functions


## Install

```
bower install mindy-sass --save
```

Add to `Gruntfile.js`:

```js
module.exports = function(grunt) {
    'use strict';

    grunt.initConfig({
        pkg: grunt.file.readJSON('package.json'),
        ...
        compass: {
            dist: {
                options: {
                    ...
                    importPath: [
                        'bower_components/mindy-sass'
                    ]
                }
            }
        },
        ...
    });
};
```
