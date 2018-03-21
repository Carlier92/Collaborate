1. Why would you use a loop? Write me a for & a while loop that prints your favorite food 10 times.

  To repeat a function multiple times

  for ( var count = 0 ; count < 10 ; count++ ) {
    console.log(`Pancakes\n`);
    }

  var count = 0;
  while (count < 10){
    console.log(`Pancakes\n`);
    count++;
  }

2. How do I try out whether my loop is working?

  Run the loop in a browser or terminal, use a funtion like console.log to print out useful information like the count number

3. What are arrays? What is an ordered collection?

  An array is a structure that stores data in an specific order. 'Ordered collection' describes how arrays and array-like constructs (such as Array objects and TypedArray objects) store data in a order by an index value (i.e. index value 0 refers to the 1st item, index value 1 refers to the 2nd item).

3. Write me an array with the names of your team and iterate over them, so all names will be printed out (using for each).

   var team = ['Chris' , 'Steven'];

   for (var count = 0 ; count < team.length ; count ++) {
     console.log(team[count]);
   }

4. What is the difference between a loop and an array? Why would you use either of them?.

  A loop is a feature that repeats a section of code (for example a function). A loop usually has one or more of the following features: a counter (counting the number of iterations), an exit condition (when the loop shall break) and an iterator (that changes the value of the counter to allow iteration).

  An array is a data storage structure.

  The differences are:
    -  A loop can be used to manipulate other code, a array can't manipulate other code, i.e. a loop is a verb, an array is a noun
    - A array can store data to be used throughout the program, each array is a specific part of code, a loop is a feature used in code, it is a building block and cannot be called from another part of code (unless it is part of another part of code)

  You'd use an array to store data and a loop to manipulate data.

5. What is happening here?

  A function multiply, that multiplies two arguments, a and b is called with a=2 and b=3.

  var multiply = function(a, b) {
  return a * b;
  };

  multiply(2, 3)
  How could we log the arguments of the code above?
  We could add: console.log(a,b) to the function multiply. The function would than look like this.
  var multiply = function(a, b) {
  return a * b;
  console.log(a,b)
  };

6. What is ‘scope’?

  Scope is a concept that describes how data/variables are available at different levels of the program, depending on how and where the dat/variables are defined. I.e. if you create local variables within a function, this data will not be available to be accessed from outside of this function.

7. Can I use my vars at the following places?

A YES
B YES
C YES
D NO

8. Why would you use an object?

  If you have a group of data that contains different sets of data with the same type, then you can use objects to store the data

9. Create an object ‘teacher', that stores the name, favorite language and a teach-function of that teacher that will alert you with some useful knowledge.

10. What are the property-names and values of the object you just created?

11. Why would you use git?

12. What is the difference between git add,git commit and git push ?
