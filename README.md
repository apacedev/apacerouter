# apacerouter
A javascript router for realtime applications

### Basic usage

**Include the file:**

``` <script type="text/javascript" src="js/apacerouter.js"></script> ```

**Javascript**
```
var apaceRouter = {

	'routes': [
		{ 
			path: '/', 
			controller: 'index',
		}, 
		{ 
			path: '/index/about', 
			controller: 'index/about' 
		},

	]

};
```

**HTML**
```
<button route="/"></button>
<button route="/index/about"></button>
```
