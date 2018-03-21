# Welcome

Welcome to this repository where you can get a first glance of collaborating on GitHub! Please answer the following questions:

# Recap

1) Why would you use a loop? Write me a for & a while loop that prints your favorite food 10 times.
-So it preforms a task repeatedly.

var i = 0;

while ( i <= 10) {
  console.log('pasta');
  i++
}

2) How do I try out whether my loop is working?
-Run the loop in console or in the terminal.


3) What are arrays? What is an ordered collection?
-It is an object to store multiple values into a single variable.
- Elements in the array will always stay in the same location.

4) Write me an array with the names of your team and iterate over them, so all names will be printed out (using for each).
var names = ['Arthur', 'Abbas'],  result = ''
names.forEach

names.forEach(function(name) {
  result += `${name} `
})
console.log(result)




5) What is the difference between a loop and an array? Why would you use either of them?.

In an Array you store values. A loop will repeat a block of code.

6) What is happening here?


```
var multiply = function(a, b) {
  return a * b;
};

multiply(2, 3)
```
-This is a anonymous function that is equal to variable multiply. It accepts two arguments. And it will return the result of multiplication of the two arguments.

7) How could we log the arguments of the code above?

 console.log(multiply(2, 3));

8) What is ‘scope’?

-A variable that is declared outside a function definition is a global variable, and its value is accessible and modifiable throughout your program. Functional Scope : Variable declared within a function with var keyword has functional scope.

9) Can I use my vars at the following places?

```
var name = Rembert

//Place A

var codaisseur = function() {
  //Place B
}
```
```
var codaisseur = function() {
  var name = Rembert
  //Place C
}

//Place D
```

-In places A+B+C you can. In place D you can not.

10) Why would you use an object?

-To group data and behaviour.

11) Create an object ‘teacher', that stores the name,
favorite language and a teach-function of that teacher that will alert you with some useful knowledge.

var teacher = {
  name: "Arno",
  favoriteLanguage: "Javascript",
  teachFunction: function() {
    alert('useful knowledge');
  }
}

12) What are the property-names and values of the object you just created?

13) Why would you use git?

14) What is the difference between `git add`,`git commit` and `git push` ?

### Clone this repository and add a file with the answers to these questions to the directory of your class. Name it 'AnswersFromYourName.md' Make sure to add a pull request and make some class mates review it!
