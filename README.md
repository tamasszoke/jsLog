# jsLog
JavaScript console logging library

<h2>Usage</h2>

Download and include jsLog.js file to your project, this is the only file you need.

```html
<script type="text/javascript" src="jsLog.js"></script>
```

Create an instance, set default color, default background, time if not need:

```javascript
var jsl = new jsLog({
	color: '#00ff00',
	background: 'rgb(100, 100, 50)',
	time: false
});
```

Write to console, accepts hex, rgb colors:

```javascript
jsl.log('some text', 'text color', 'background color');
```

<h2>Options</h2>

```javascript
jsl.color('color'); // Set font color (default: black)
jsl.background('color'); // Set background color (default: none)

jsl.time_on(); //Logging with time (default)
jsl.time_off(); // Logging without time

jsl.on(); // Enable logging (default)
jsl.off(); // Disable logging
```

<h2>License</h2>

<b>The MIT License (MIT)</b><br/>
Copyright (c) 2016 Tamas Szoke

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

https://opensource.org/licenses/MIT
