## Functions# #functions 
- Function tells computer to do certain things.
- Functions take **arguments** to give the computers extra information.
```jsx
drawBox(red);
```
- **red** is an argument.
- **drawBox()** is the name of function.
- **drawBox(red)** calling function with argument **red**.
---

## Arguments #arguments
- An argument is an extra information given to a function that tells it how it should run.
- Arguments are placed inside the parentheses of a function call.
- Not all functions take arguments and some functions take multiple arguments.
```jsx
drawBox(red);
print(hello);
```
- **red** is the argument for the drawBox() function.
- **hello** is the argument for the print() function.
---

## Strings
- Letter, words and sentence are called **strings ** in coding.
- Quotation mark are used to show the start and end of string.
```jsx
drawBox('royg')
```
- 'royg' is a string used in drawBox() function as an argument to create red, orange, yellow and green boxes.

## function in function
```jsx
drawBox(pickrandom(color))
```
- In this we use pickrandom() functions.

# Variables
- They allow you to reference of small piece of information for multiple times. In JavaScript variables are defined with **var** then giving variable a unique name.
```jsx
var myVariable;
myVariable = 'I created a variable';
print(myVariable)
myVariable = 'I changed the value';
print(myVariable);
```
- Variable myVariable  is declared, then it's given a value; then printed out.
- The variable's value then updated and printed out again with a new message.

```jsx
var drink = 'juice';
print(drink);
drink = 'water';
print(drink);
```

## Variable Chaining
```jsx
var x = 7
var y = x
print(y);
```
- It's a variable chaining.
- It's going to print 7.

## Arrays [ ]
In JavaScript an array is list of items.
The array can be different data types: numbers, strings and even other arrays.
An array inside another array is called **Array Nesting.**
```jsx
var myArray = ['apple', 'blue', 50, 10, [50, 10]];
````
- It has 5 items.
- It contain numbers, strings and an array, which itself has two items that are numbers.

```jsx
var answer = pickrandom([
	'yes',
	'no',
	'ok'
	'go'
]);
print(answer);
````

```jsx
var ingredients = ['flour', 'egg', 'milk'];
cook(ingredients);
````
- Arrays are always in [ ] square brackets.

## Array Indexing [ ]
- In most programming languages also in JavaScript arrays are indexed started at 0.
- The first of an array has an index of 0.
- For example -> myArray[0] accessed the yes and myArray[3] accessed 4th item.

```jsx
var groceris = ['apple', 'banana', 'guava', 'oranges'];
var fruit = groceries[2]
````
- fruit item holds the second third item in the array, which is *guava*.

# If Statement
## If Statement
- If statement allow you to run a specific code when a test is true. 
- The code inside the parentheses **()*** is test.
- If  test is true then the code inside **block {}** runs.
- If test is not true, then the code inside **block{}** doesn't run.
```jsx
var aNumber === 5;
	if (aNumber === 5) {
		drawBox(blue);
} 
if (aNumber === 4) {
	drawBox(red);
}
````

## Equality Operator
Compares whether two things are equal to each other.
```jsx
print(10 === 5);
print(5 === 5);
````
> JavaScript is case Sensitive . 'Tails', 'tails','TAils' are not equal.

```jsx
var answer = (pickrandom[
	'heads'
	'tails'
])
print(answer);
if (answer === 'heads') {
	drawBoxes('gwg ggg wgw');
}
if (answer === 'tails') {
	drawBoxes('gwg wgw www');
}
````
## If..else Statement
If..else statements perform a test to decide which code to run.
- If  the test is true, if block {} runs.
- If the test is false, else block {} runs.
```jsx
var number = pickRandom(10);
	if(number === 5){
		print("Number is 5!");
} else {
	print("Number is not 5!");
}
````

## Does not Equal Operator[ !== ]
Compares whether two thing (numbers, variables) are not equal.
```jsx
var number
if (number !== 5; {
	print("Number is not 20");
}
if (number !== 10); {
	print("Number is  not 20");
}
````
```jsx
var bananas;
var numberBananas;
if (bananas !== 'green') {
	if(numberBananas > 10) {
		print("Let's make a shake");
	}
}
````

## Plus Operator (+)
Adds two values together. 
The operators most commonly used in numbers and strings.

```jsx
var result = 10 + 5;
var newResult = 'Siddhant' + 'Shukla'
````
## Minus Operator (-)
Subtracts value on the right side of the operator from value of left side of operator.

```jsx
var result = 10 - 5;
````
```jsx
var x = 5;
x = x + 1;
print('x is' + x);
x = x -1;
print('x is now' + x);
```
## Multiply Operator (\*)
Multiplies the value on the left side to the value on the right side.
```jsx
var multiple = 10*5;
```
## Divide Operator(/)
Divides the value on the left of / operator by the value on the right side.
```jsx
var number = 10/5;
```


## And Operator (&&)
- Combines two statements into a *true* or *false* value. 
- It becomes *true* only if the left and right side are both *true*, otherwise it's *false*

```jsx
if (1 < 2 && 5 > 0) {
	print("Yes");
} else {
	print("No");
}
```
```jsx
var pincode = 10;
var fonudKey = (['yes', 'no']);
print('pinNumber is' + pincode);
print('key is' + foundKey);
if(foundKey === 'yes' && pincode === 10){
	print("You can Open it.");
} 
if (foundKey ==== 'no' && pincode === 10){
	print("You have pincode but your key is not found yet.");
}
```
## Greater than Operator(>)
Compares whether the left side is greater than right side.
```jsx
if (5 > 4) {
	print("This will always print because 5 is always greater than 4")
}
```
## Less than Operator(<) 
Compares whether left side is lesser than right side.
```jsx
if ('apples' < 'bananas'){
	print('This is going to print')
}
```
- It will print because 'b' in bananas is alphabetically greater than 'a' in apple. 

## Or Operator(||)
Combines two statements into a *true* or *false* value. 
- It becomes *true* if either left or right side is true.
- It's only false if both sides are false.

```jsx
if (2 === 4 || 1+1 ===2){
	print("Atleast 1 is true.");
} else{
	print("Both are false.");
}
```
# Loop
A loop repeats same line of code over and over.
The lines to repeat are surrounded by curly braces {}  
There are many ways to execute a loop {"particularly in JavaScript"}

## for...of loop
- A loop repeats the section of code within the curly brackets {}. 
- In JavaScript a for of loop goes through 	each element in array, string repeating the code for each element.
```jsx
var groceries = ['apple', 'bananas', 'yogurt'];
for (var element of groceries) {
	print(element);
}
```
- Each item in the *groceries* array will be printed out on it's own line.

```jsx
for (var x of ['red', 'blue', 'green', 'yellow', 'violet', 'indigo']){
	drawBox(x);
	drawBox(x);
	drawBox(x);
	newLine();
}
```
- 3 times red then new line 3 times second color then new line 3 times third color

## Classic For loop
In Java Script, classic for loop repeats code in { }  for a specific number of times. It is defined in three parts :
- The first part happens before the loop starts and define looping variable (var i = 0;)
- The second part is a test that determines if the loop should keep repeating (i < 10;)
- The third part updates looping variable each time the loop repeats (i = i + 1;)

```jsx
print('The loop will go as long as i is less than 10');
for(var i = 0; i < 10; i = i + 1) {
	print(i);
}
```
```jsx
for (var i = 10; i > 0; i = i - 1;){
	print(i);
}
print('Happy New Year');
```

## Nested loop
A nested loop is a loop within another loop. Although nested loop can be useful, if you have too many it can make code execution slow or difficult to understand.

```jsx
for (var outerNumber of [1, 2, 3, 4, 5]){
	for (var nestedNumber of [6, 7, 8, 9]){
		print(outerNumber, nestedNumber);
	}
}
```

```jsx
for (var band of [
	'Raging'
	'Happy'
	'Hungry'
]) {
	for (var noun of [
		'Pharmacy'
		'Squids'
		'Twins'
	]) {
		print('The' + '' + band + '' + noun);
	}
}
```
-  Raging goes to all noun
- Happy goes to all noun
- Hungry goes to all noun

## Object { }
An object stores multiple values that have properties or key names. 
This allows them to be easily accessed later in the code.
```jsx
var groceris = {
	apple: 5,
	bannana: 2
};
```
-  apple and bananas are properties of object groceries.
-  5 and 2 are associated value with those properties.
-  groceries.apple, for instance is equal to 5.

## Accessed a Property
An object can store multiple properties of information inside one variable. 
Dot notation is used to access a property of an object. 
**objectName.propertyName**

```jsx
var objectName = {
	propertyName: 'Coding is fun',
	otherPropertyName: 'This is also a key value'
};
print(objectName.propertyName);
```
**After curl brackets there is semi-colon is used"
**Comma is also used after  property**
- This will print out 'Coding is fun.'
```jsx
var name = {
	first: 'ghost',
	second: 'man',
	last: '01'
};
print('Your name is:' + name.first + name.second + name.last);
```

```jsx
print(rgbObject.blue);
if (rgbObject.blue > 200){
	drawBox(rgbObject);
}
```

```jsx
var teaCup = {red: 20, blue: 10, white: 5};
var sugar = teaCup.blue
```





















































