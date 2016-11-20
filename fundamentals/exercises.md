# JavaScript fundamentals - exercices

### Given the following code:

```js
var s = "Hello";
var x = s.toLowerCase();
var l = s.length;
```

**1. What are the types of the following:**

1. `s` :String  
2. `x` : String
3. `s.toLowerCase(  )` : hello   
4. `s.toLower  Case` :SyntaxError: Unexpected identifier 
5. `s.length` : 5 
6. `l`  : nummber  

----

### 2. In `var x = 5 + 6;`, what is `+`?

1. Function 
2. Operator (yes)  
3. Number  
4. Aggregator  

----

### 3. In `var x = 5 + 6;`, what is `var`?

1. Variable  (yes)
2. Keyword  
3. Operator  
4. Constant  

----

### Given the following code:

```js
var x = z[y];
```

**4. What is `y`?**

1. Index  (yes)
2. Key  
3. Index or key  
4. Array  

----

### Given the following code:

```js
var y = 1;
var x = [1, 2, 3];
var z = x[y];
```

**5. What is `y`?**

1. Index  
2. Key  
3. Index or key  (yes) 
4. Array  

----

### Given the following code:

```js
var joe = {
  name: 'Joe',
  age: 24
};
var joesName = joe.name;
var joesAge = joe['age'];
```

**6. What is `'age'` in the last line?**

1. Index (yes)
2. Key
3. Property
4. Object

**7. What are `name` and `age` of the object `joe`?**

1. Index
2. Key
3. Object 
4. Property (yes)

----

### Given the following code:

```js
var y = 'length';
var x = [1, 2, 3];
var z = x[y];
```

**7. What is `y`**

1. Index  
2. Key  
3. Index or key  (yes)
4. Array  

**8. What is the element for index `1` in array `x`?**  Object

**9. Fill in: "The value of the (...) `length` of `x` is (...)"** 3

----

### 10. What is the name of these functions?

1. `function a() { return true; }`:  Function Declaration   
2. `var a = function b() { return true; }`  :Named function expressions
3. `var c = function () { return true; }` : function expressions 

----

### 11. Write a function that has two parameters called `first` and `second`
Fucntion MyFunction(first, second){};
----

### 12. Write a function call that passes three arguments. MyFunction(one , tow , tree);

----

### 13. Write code for the following

1. Declare a variable called `x` and initialize it with the string "Hello".   var x = "Hello";
2. Declare a variable called `y` and initialize it with the property `length` of `x`.  var y = x.length;
3. Declare a variable called `z` and initialize it with the result of calling the method `toUpperCase` on `x`  var z = x.toUpperCase();
4. Declare a function called `myFunction`. This function should take two arguments, and should call the second argument with the first argument as its argument. Then, declare a variable called `f` and initialize it with an empty anonymous function, and call `myFunction` with the arguments `10` and `f`.
 
 function myFunction(a, b) {

	return b(a);

	}

	var f = function () {

	myFunction(10, f);

}  

----

### 14. Explain as precisely as possible (in English) what the following code does, line by line

(Tip: it should look like the items in the previous question!)

```js
var s = "HackYourFuture";
var i = s.indexOf("Your");
function sum(a, b) { return a + b; }
var s = sum(4, 5);
var r = Math.sqrt(s);
```
1-We Declare a variable called s and initialize it with the string "HackYourFuture".
2-We Declare a variable called i and initializing it with the result of calling the method 'indexOf' 
and we run the indexOf method on the String "Your" .
3-we have function called 'sum' with tow paramiters (a,b)  and we return  a+b  the result
4-we Declare a varibale called s  and sum the paramters 4,5  the result is 9
5-we Declare a varibale called r 
----

### 15. Indicate for each of these whether it is an expression or a statement:

1. `l` expression  
2. `l = 4;`  statement
3. `l == 4`  expression
4. `if (l == 4) { console.log("yes"); }`  statement
E. `console.log("yes");`  statement
F. `"yes"`  expression 
G. `console.log(l == 4 ? "yes" : "no")` statement 
H. `function a() { return 4; }` statement 
I. `var a = function () { return 4; }`  statement

----

### 16. How can you tell whether something is a statement?
((At its simplest terms, expressions are evaluated to produce a value. On the other hand, statements are executed to make something happen.))
----

### 17. How can you tell whether something is an expression
((At its simplest terms, expressions are evaluated to produce a value. On the other hand, statements are executed to make something happen.))
----

### Given the following code:

```js
var s = "Hello".toLowerCase();
var l = s.length;

function sum(a, b) {
  return a + b;
}
var max = function (a, b) {
  return a > b ? a : b;
}

var s1 = sum(4, 5);
var s2 = 4 + 5;

if (s2 == s1) {
  console.log("same");
} else {
  console.log("not same");
}
```

**18. List all 11 *statements* in the code above**

**19. List all 23 *expressions* in the code above (BONUS!)**
