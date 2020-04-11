Node
Node.js is a server-side platform built on google chrom's javascript Engine (V8 Engine). Node.js was developed by Rayan Dahl in 2009. and its latest version is v0.10.36

Node.js uses an event-driven
non-blocking I/O Model 	// jiski request ka response pahle milega wo pahle output dega
Lightwegiht and efficient
perfect for data-intensive real time application


### Download Node.js:-
Go to Nodejs.org website --> LTS version download and install

### Check install Node:-
Open CMD --> node -v

### Check NPM:-
Open CMD --> npm -v

### CMD ke through run program:-
Open CMD --> node
```node
console.log("hello mohit")

const a=10
const b=20
a+b
output:- 30
```

### exit node:-
Type ctrl + C  two times 

### Create pakage.json
in CMD line go to node folder(when you create cd folderName) and 
```node
npm init
```

Write Example:-
open folder and create file index.js
```node
console.log("hello mohit")

const a=10;
const b=20;
c=a+b;
console.log(c);

open terminal/CMD:- node file_name
```

### Anonymous function
Anonymous function wo hota hai jis function ka koi naam nahi hota hai
```node
var person = function(){	
}

var person = function(){
console.log("hello")	;
}
person(); //hello 

var parson=function(a,b){
	var c=a+b;
	console.log(c);
}
person(4,5);
```

### Arrow Function:-
var user = () => consol.log("hello");


### Global Object:-
__dirname
__filename
__require	// var req = require(./main.js)
__console
__buffer	//tempary memory alocate hokar temapry value hold karta hai
__module
__exports

console.log(__dirname);	//users/mohit/desktop/node
console.log(__filename);	// users/mohit/desktop/node  or //users/mohit/desktop/node/index.js(file name or directory name bhi batata hai)



### Template String

var name = 'mohit';
var age = 27
console.log("hi %s You are %s age", name,age)
console.log("hi "+name+" You are "+age+" age", name,age)	//Javascript mai aise likhte hai
console.log("hi %{name} You are %{age} age");	//tempalte string mai aise likhte hai

### create class
class users{
	constructer(){
	this.name = "mohit saxena";
	this.age = 27;
	}
	getname(){
		this.email = "mksaxena27@gmail.com";
		return this.name;
	}
	getage(){
		return this.age;
	}
		getemail(){
		return this.email;
	}
}

var user = new Users();
consol.log(user.getname());
consol.log(user.getemail());

### prototype

oops mai ek class ko dusre class mai acess karne ke liye inhrit karte hai. same node mai prototype use karte hai
var student = function(){
	this.name = "mohit saxena";
	this.age = 27;
	}

student.prototype={
	address = "new delhi";
	getname: function(){
		return this.name;
	}
}

address ko add karna hai bin upar wale function ko change kiye hue


var std = new student();
consol.log(std.name);




