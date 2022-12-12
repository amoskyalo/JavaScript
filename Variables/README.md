# JavaScript Variables.

### What is a variable
A variable is container for a value/name of a storage location.

### Declaring a variable
If you want to use a variable, you should first create it. This is what is called declaring a variable. JavaScript gives us three keywords to use when declaring variables
        `var`
        `let`
        `const`
To declare a variable, we write tyle the keyword followed by the name we want to give to the variables:
    `let name; //here we have declared a variables called name`
    `const age; //here we have declared a variables called age`

`const` keyword is different from the rest. It stands for constant variables. This means that once we declare a variable with `const` keyword, we cant re-assign values to them again.

### Initializing a variable
No, after we have declared a variable, we have to assign a value to it. To assign a value to it, we type the variable name, followed by equal (=) sign and then the value we want to give to it
    `let age = 20 //here we have declared a variable called age, and then assigned 20 as its value`

### Types of variables
There are two types of variables,
    - Global Variables
    - Local Variables

 - Local Variables are declared inside a block or a function and are only available inside that block. This means that we cant access that variable outside that block
    `function personName(){ let name = myName}`
In the above example, name is only declared inside that funcion, this means we cant access name variable outside the function

 - Global Variables are declared outside functions or block. This means they are available globaly.
    `var name = myName //this variable is not declared inside any function, and can be accessed anywhere in our code`

### Variable types
There are different data we can store in our variables. We can list them and then look at them in depth later:
    - Numbers
    - Strings
    - Arrays
    - Objects
    - Booleans

### Dynamic Typing
JavaScript is a dynamically typed Language, which means, unlike many other languages, you dont have to specify what data type a variable will contain. 



### Rules of naming variables
You can give a variables any name, as long as its a name anyone will understand when they look at your code. But we have some rules that we should follow as we name variables;
 - Avoid JavaScript reserved words
 - Dont start a variable with a number or underscore
 - Make variables intuitive - so they describe the data they contain
 - Variables are case sensitive
