# packaged angular-resource

This repo is for distribution on `npm` and `bower`. The source for this module is in the
[main AngularJS repo](https://github.com/angular/angular.js/tree/master/src/ngResource).
Please file issues and pull requests against that repo.

## Install

You can install this package either with `npm` or with `bower`.

### npm

```shell
npm install angular-resource
```

Then add `ngResource` as a dependency for your app:

```javascript
angular.module('myApp', [require('angular-resource')]);
```

### bower

```shell
bower install angular-resource
```

Add a `<script>` to your `index.html`:

```html
<script src="/bower_components/angular-resource/angular-resource.js"></script>
```

Then add `ngResource` as a dependency for your app:

```javascript
angular.module('myApp', ['ngResource']);
```

## Documentation

Documentation is available on the
[AngularJS docs site](http://docs.angularjs.org/api/ngResource).

