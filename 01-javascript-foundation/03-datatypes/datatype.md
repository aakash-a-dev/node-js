# Discovering Data Types in JavaScript

Hello there! Today, we're diving into the awesome world of **JavaScript Data Types**. Buckle up, and let's explore the different ways JavaScript understands and uses information.

## 1. **Primitive Data Types**

### a. **Number**
Think of numbers, just like your age or the temperature outside.

````js
let age = 15;
let temperature = 25.5;
````

### b. **String**
Strings are words or phrases. Imagine your name or a friendly message.

````js
let name = "Sam";
let message = 'Hello, World!';
````

### c. **Boolean**
Booleans are like true or false switches. Are you a student? Yes or no?

````js
let isStudent = true;
let hasPet = false;
````

### d. **Null**
Sometimes we intentionally say there's nothing, like an empty box.

````js
let noValue = null;
````

### e. **Undefined**
When we forget to give something a value, it's undefined, like a blank space.

````js
let undefinedVariable;
````

### f. **BigInt**
For really, really big numbers, we use BigInt. Just put an 'n' at the end.

````js
let bigNumber = 9007199254740991n;
````

### g. **Symbol**
Symbols are like secret codes. Each one is unique.

````js
const secretCode = Symbol('hiddenMessage');
````

## 2. **Composite Data Types**

### a. **Object**
Objects are like treasure chests with different things inside.

````js
let person = { name: 'Alex', age: 15, isStudent: true };
let book = { title: 'Adventure Awaits', pages: 150 };
````

### b. **Array**
Arrays are lists of things, like your favorite colors or numbers.

````js
let colors = ['red', 'green', 'blue'];
let favoriteNumbers = [7, 15, 23, 42];
````

## 3. **Special Data Types**

### a. **Function**
Functions are like magical spells, doing something special when you say the magic words.

````js
function sayHello(name) {
  return 'Hello, ' + name + '!';
}
````

Understanding data types helps us talk to computers and make them do amazing things. Keep exploring, and have fun coding! 🚀✨
