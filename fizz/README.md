#Odin Project Problem Solving Exercice
##Fizzzz

###The Problem

The user will input a number and the program should give back all the numbers untill that inputs value with 3 exceptions:

- __Fizz__ multiples of 3 ( a number that divided by 3 leaves 0 remainder (%));
- __Buzz__ for multiples of 5 ( a number that divided by 5 leaves a 0 remainder (%));
- __FizzBuzz__ for multiples of 3 and 5 (both remainders are 0).

__Input__: one number;
__Output__: array;
(No need for UI)

##Requested functions:

- Function that outputs sequence of number from input to zero; (proper method or loop??)
- Conditional to evaluate if number is multiple of 3, 5 or both;
- Display output.

##Pseudo-Code:

__Function Fizz__ checks if __currNumber__ divided by 3 has 0 remainder,
being true results in __Fizz__;
being false results in the __currNumber__.

__Function Buzz__ checks if __currNumber__ divided by 3 has a 0 remainder;
being true results in __Buzz__;
being false results in __currNumber__.

__Function FizzBuzz__ checks if number is __Fizz__ and __Buzz__.

__Function Add to Array__ checks if the __currNumber__ is __Fizz__, __Buzz__, __FizzBuzz__ or just the __currNumber__;

Create a __loop__ to build the array, subtracting 1 to each number from __Input__ to 0, passing the __currNumber__ through the conditional functions( __Fizz__, __Buzz__, and __FizzBuzz__)
printing the result.