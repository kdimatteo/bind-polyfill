This repo exists in order to define a bower package (bind-polyfill), I am not the author of this code.

This polyfill is courtesy of [Mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/bind#Compatibility) and licensed in the public domain as it was [authored After August 2010](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/bind$revision/5019) and, per the [Mozilla Licensing Terms](https://developer.mozilla.org/en-US/docs/MDN/About#Copyrights_and_licenses), im the public domain.


This method is also available in the broader [polyfills](https://github.com/inexorabletash/polyfill) bower package.

Not needed for IE9+, FF4+ Webkit, Chrome 12+ (_but is needed for PhantomJS_). See [ES5 Compatibility Table](http://kangax.github.io/es5-compat-table/#Function.prototype.bind) for details. 

`bower install bind-polyfill --save`

If you're managing packages with npm please refer to [bindpolyfill](https://www.npmjs.com/package/bindpolyfill)

