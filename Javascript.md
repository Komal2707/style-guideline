# Javascript Style Guide



## Variables

```javascript
// function name should be camel case
let variableName = 'wow'
```



## Single quotes

When using strings, always use the single quote to wrap them.

```
let variable = 'wow' // use single quote like this

let obj = {
	value: 'wow', // single quote here as well
}
```



## Array

```javascript
let array = ['hello', 'wow']; // single like array

// multi line array, always use comma at the end of the string
let array = [
    'hello',
    'wow',
];
```



## Object

```javascript
let obj = { key1: wow }; // always have 1 char space between { } single key based object

// and if there are more than 1 key, just do the multiline way

let obj = {
	key1: 'hello',
	key2: 'wow',
};
```



## Semicolon

```javascript
// As you know semicolon is optional in javascript
// So I guess its just preference of developer to use or not use it
```



## Function

```javascript
//function name should be camel case
// no space after function name
// one single space character after ()
// starting curly brace on same line
// ending curly on its own line
// return statement should have one empty line before it
function functionName() {
    let wow = 'wow';
    
    return wow
}
```



## All above structure under same place

```javascript
// function assigned on variable
let functionName = function() {
	let wow = 'wow';
    
    return wow;
}

// comma should have 1 space after
function newFunctionName(obj, wow) {
    return [obj, wow];
}

let obj = {
    wow: 'wow',
    foo: 'bar',
};

let arr1 = ['arr1', 'arr2'];

let arr2 = [
    'arr1',
    'arr2',
];
```

