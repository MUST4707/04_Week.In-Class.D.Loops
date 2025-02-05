Introduction to While Loops
===========================

A **while loop** allows you to repeatedly execute a block of code as long as a specified condition is `true`. This is useful for running a loop when the number of iterations is not known beforehand.

Basic While Loop
----------------

The syntax of a while loop is:

    while (condition) {
        // Code to be executed
    }

Example:

    let count = 0;
    while (count < 5) {
        console.log("Count is: " + count);
        count++; // Increment count to avoid an infinite loop
    }

Iterating with a While Loop
---------------------------

We can use a while loop to iterate through an array:

    let fruits = ["Apple", "Banana", "Cherry"];
    let i = 0;
    while (i < fruits.length) {
        console.log(fruits[i]);
        i++;
    }

Breaking Out of a While Loop
----------------------------

Use the `break` statement to exit a while loop prematurely:

    let number = 0;
    while (true) {
        console.log("Number is: " + number);
        if (number >= 3) {
            break;
        }
        number++;
    }

Conclusion
----------

While loops are a powerful way to repeat actions until a certain condition is met. They are particularly useful for scenarios where the number of iterations is unknown in advance.
