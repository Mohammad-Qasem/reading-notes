# Operators and Loops.

-omparison and Logical operators are used to test for true or false.

## Comparison Operators.

Comparison operators are used in logical statements to determine equality or difference between variables or values.

* Examble:

Given that x = 5, the table below explains the comparison operators:

| Operator      | Description | Comparing      | Returns |
| ----------- | ----------- |-----------  | ----------- |
| ==      | equal to       |	x == 8       | false       |
| ===   | equal value and equal type       | x === 5   | true       |
| !=  | not equal      |x != 8  | true       |
| !==   | not equal value or not equal type      | x !== 5  | false       |
| >   | 	greater than      | 	x > 8   | false     |
| <  | less than      | x < 8   | true       |
| >=   | greater than or equal to       | 	x >= 8   | 	false      |
| <=  | less than or equal to      | 	x <= 8   | 	true      |

## Logical Operators.

* Logical operators are used to determine the logic between variables or values.
 
* Examble:

Given that x = 6 and y = 3, the table below explains the logical operators:

| Operator      | Description | Comparing      
| ----------- | ----------- |-----------  | 
| &&    | and      |	(x < 10 && y > 1) is true      
| !  | not       | 	!(x == y) is true


also                 
                      || witch means (or) and gives (x == 5 || y == 5) is false


# for and while loops.

Loops can execute a block of code as long as a specified condition is true.

## The For Loop.

The for loop has the following syntax:

              for (statement 1; statement 2; statement 3) {
                 // code block to be executed
              }
              
* Statement 1 is executed (one time) before the execution of the code block.

* Statement 2 defines the condition for executing the code block.

* Statement 3 is executed (every time) after the code block has been executed.      

-Example:

                for (i = 0; i < 5; i++) {
                 text += "The number is " + i + "<br>";
                }


## The While Loop

The while loop loops through a block of code as long as a specified condition is true.

-the benifite of using while loop that it can itirate for infinite number of loops which make it uniqe than foor loop.

* Syntax

                           while (i < 10) {
                            text += "The number is " + i;
                               i++;
                            }

                        

