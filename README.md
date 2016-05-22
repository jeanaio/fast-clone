<center>
	<img src="https://raw.githubusercontent.com/codeandcats/fast-clone/master/logo.png" />
</center>

The *fastest deep cloning* function on NPM that supports all the following types:
- Objects
- Arrays
- Dates
- Strings
- Numbers
- Booleans

## Installation
```
npm install fast-clone --save
```

## Usage
Can be used in Node.js or you can use in Browser either using Browserfy/Webpack or the global clone function. 
```
var clone = require('fast-clone');

var a = {
	name: 'Natasha Rominov',
	age: 30,
	skills: [
		'Pistols',
		'Espionage'
	],
	dateOfBirth: new Date('1986-05-21T00:00:00.000Z')
};

var b = clone(a);

b.skills.push('That grabby thing she does with her legs');

console.log(a.skills)
console.log(b.skills);
```

Output will be:
```
['Pistols', 'Espionage']
['Pistols', 'Espionage', 'That grabby thing she does with her legs']
```

## Got an Issue or Feature Suggestion?
Then [create an issue on GitHub](https://github.com/codeandcats/fast-clone/issues) and I'll fix/add it asap. :)

 
