#unveil.js 
Modified version of the original Plugin by plugin by [Luís Almeida](https://github.com/luis-almeida/unveil).

* Parameters are now passed via object
* Added option to pass callback handler (will be executed after lazy loading):

```javascript
var 
  logHandler = function() {
		console.log($(this).attr("src") + " loaded");
	},
	options = {
		"threshold": 300, 
		"callback":logHandler
	};

$("img").unveil(options);
```

Click [here] (http://htmlpreview.github.io/?https://github.com/dreimsbach/unveil/blob/master/index.html) for a demo.

###License
Unveil is licensed under the [MIT license](http://opensource.org/licenses/MIT).
