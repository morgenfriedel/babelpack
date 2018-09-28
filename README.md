# Babelpack

Babelpack is a simple starting place for developers who value modular code, uncluttered workflows, and next generation JavaScript.

To get started, simply run `npm install`. Thanks to Babel, you'll be able to use all of the wonderful features of ES6 JavaScript like this very handy `import` feature:

````
import jQuery from 'jquery'
import { accounting } from 'accounting'
import './lib/jquery.dataTables.min.js'
```

Webpack will take care of combining everything into a single file. Keep in mind that this repository is only a starting place. You should install any extra packages or dependencies you might need from `npm` and edit the `webpack.config.js` file to fit the needs of your project.