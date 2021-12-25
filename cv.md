# Zhan Yessimbekov
***

### Contact Contact information:
##### Phone: `+548 654 215`

__E-mail:__ lol@lol.com

__Telegram:__ 

***
# Briefly About Myself:








***
# Skills and Proficiency:




***
# Code example:
```javascript
function foo() {
	console.log( this.bar );
}

const bar = "global";

const obj1 = {
	bar: "obj1",
	foo: foo
};

const obj2 = {
	bar: "obj2"
};

foo();				    // "global"
obj1.foo();			  // "obj1"
foo.call( obj2 );	// "obj2"
new foo();        // undefined
```
