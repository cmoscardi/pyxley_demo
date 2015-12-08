# metricsgraphs Heroku Example
This is forked form [pyxley](https://github.com/stitchfix/pyxley) and is a heroku-runnable example 
of a pretty dashboard.

Instructions:
- Once you have a heroku app, you'll need both the python buildpack and the nodejs buildpack. 
- [See here](https://devcenter.heroku.com/articles/using-multiple-buildpacks-for-an-app) for instruction.


# metricsgraphics.js Example
This example showcases the integration of the [metricsgraphics.js](http://metricsgraphicsjs.org/)
library for time-series data.

# How to Install
Make sure pyxley is installed first (run `python setup.py install`).

## NPM
Install NPM (e.g brew install node). Then run `npm install -g` in the directory containing
package.json. `-g` will make bower available globally.

### Bower
Create a file called `.bowerrc` containing
```json
{
    "directory": "./project/static/bower_components"
}
```
This will tell bower where to install the packages.

Now run `bower install` to install the bower components.

# Flask
Run `python app.py`.



