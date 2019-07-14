## JavaScript Snippet Pack for CodeExpander

A snippet pack to make you more productive working with JavaScript.

This extension ships a bunch of useful code snippets for the JavaScript and TypeScript editors.

Here's the full list of all the snippets:

## Console

### [cd] console.dir

```javascript
console.dir(%c%);
```

### [ce] console.error

```javascript
console.error(%c%);
```

### [ci] console.info

```javascript
console.info(%c%);
```

### [cl] console.log

```javascript
console.log(%c%);
```

### [cw] console.warn

```javascript
console.warn(%c%);
```

### [de] debugger

```javascript
debugger;
```

## DOM

### [ae] addEventListener

```javascript
%c%document.addEventListener('%c%load', function(e) {
	%c%
});
```

### [ac] appendChild

```javascript
%c%document.appendChild(%c%elem);
```

### [rc] removeChild

```javascript
%c%document.removeChild(%c%elem);
```

### [cel] createElement

```javascript
%c%document.createElement(%c%elem);
```

### [cdf] createDocumentFragment

```javascript
%c%document.createDocumentFragment();
```

### [ca] classList.add

```javascript
%c%document.classList.add('%c%class');
```

### [ct] classList.toggle

```javascript
%c%document.classList.toggle('%c%class');
```

### [cr] classList.remove

```javascript
%c%document.classList.remove('%c%class');
```

### [gi] getElementById

```javascript
%c%document.getElementById('%c%id');
```

### [gc] getElementsByClassName

```javascript
%c%document.getElementsByClassName('%c%class');
```

### [gt] getElementsByTagName

```javascript
%c%document.getElementsByTagName('%c%tag');
```

### [ga] getAttribute

```javascript
%c%document.getAttribute('%c%attr');
```

### [sa] setAttribute

```javascript
%c%document.setAttribute('%c%attr',  %c%);
```

### [ra] removeAttribute

```javascript
%c%document.removeAttribute('%c%attr');
```

### [ih] innerHTML

```javascript
%c%document.innerHTML = '%c%elem';
```

### [tc] textContent

```javascript
%c%document.textContent = '%c%content';
```

### [qs] querySelector

```javascript
%c%document.querySelector('%c%selector');
```

### [qsa] querySelectorAll

```javascript
%c%document.querySelectorAll('%c%selector');
```

## Loop

### [fe] forEach

```javascript
%c%array.forEach(function(item) {
	%c%
});
```

## Function

### [fn] function

```javascript
function %c%methodName (%c%arguments) {
	%c%// body
}
```

### [afn] anonymous function

```javascript
function(%c%arguments) {
	%c%// body
}
```

### [pr] prototype

```javascript
%c%object.prototype.%c%method = function(%c%arguments) {
	%c%// body
}
```

### [iife] immediately-invoked function expression

```javascript
(function(%c%window, %c%document) {
	%c%// body
})(%c%window, %c%document);
```

### [call] function call

```javascript
%c%.call(%c%context, %c%arguments)
```

### [apply] function apply

```javascript
%c%.apply(%c%context, [%c%arguments])
```

### [ofn] function as a property of an object

```javascript
%c%: function(%c%arguments) {
	%c%// body
}
```

## JSON

### [jp] JSON.parse

```javascript
JSON.parse(%c%);
```

### [js] JSON.stringify

```javascript
JSON.stringify(%c%);
```

## Timer

### [si] setInterval

```javascript
setInterval(function() {
	%c%// body
}, %c%1000);
```

### [st] setTimeout

```javascript
setTimeout(function() {
	%c%
}, %c%1000);
```

## Misc

### [us] use strict

```javascript
'use strict';
```

### [al] alert

```javascript
alert('%c%msg');
```

### [co] confirm

```javascript
confirm('%c%msg');
```

### [pm] prompt

```javascript
prompt('%c%msg');
```

## License
[MIT License](https://raw.githubusercontent.com/akamud/vscode-javascript-snippet-pack/master/LICENSE)