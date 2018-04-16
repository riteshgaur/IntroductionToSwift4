## A Simple Print

`print("Hello Swift")`

Notice, there is no need for a semi-colon (;)

if you accidently add one, no need to worry. However it is highly recommended to avoid

Output: 

**Hello Swift**



## Commenting the code

You can comment a line of code by adding "\\" at the beginning of the code or you can comment a block of code my placing it in "/*    */" 

For example

`//print("Hello Swift")`

and 

`/*`

`//print("Hello Swift")`

`//print("Hello World")`

`//print("This is a comment")`

`*/`

## Creating variables.

 In Swift, we use **var** keyword to create a variable.

`var myVariable = 100`

name of variable is *myVaiable*. Such style of nameing is called *Camel case*, camel caps or more formally as medial capitals. CamelCase is named after the "humps" of its capital letters, similar to the humps of a Camel

Let's create a variable that make more sense.

`var myName = "Ritesh"`

`var myAge = 30`

let's print these variables

`print(myName)`

`print(myAge)`

Output:

**Ritesh**

**30**



if, we want to go little fancy. We can use the following:

`print("Hi, My Name is \(myName) and I am \(myAge) years old")`

Output:

**Hi, My Name is Ritesh and I am 30 years old**



let's create 3 more variables and do some math.

`var apples = 10`

`var oranges = 20`

`var kiwi = 30`

print("I have \(apples+oranges+kiwi) number of fruits")

print("I eat 2 apples so now I have \(apples-2) Apples")

Output:

**I have 60 number of fruits**

**I eat 2 apples so now I have 8 Apples**

`var price = 4.78`

print("Total price I paid for all the fruits is $\(price)")

**Total price I paid for all the fruits is $4.78**

Similarly you can do other math operations such as minus, divide, multiplicatoin, division, etc



## Creating Constants

We can create Constants using **let** keyword, for example

`let myRollnumber = 20180407`

Because it's a constant, means it will not change. If we try to change its value. It will see an Error!

`myRollnumber = myRollnumber + 1`  

> [Error:Cannot assign to value: 'myRollnumber' is a 'let' constant]