## Given a three-digit number. Find the sum of its digits.
```
Example input
123

Example output
6
```
```
Theory
If you don't know how to start solving this assignment, please, review a theory for this lesson:
https://snakify.org/lessons/integer_float_numbers/

You may also try step-by-step theory chunks:
https://snakify.org/lessons/integer_float_numbers/steps/1/
```
```
num = int(input())
a = (num%10)
b = ((num//10)%10)
c = ((num//10)//10)
sum = a+b+c
print(sum)
```
