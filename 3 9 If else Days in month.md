## Given a month - an integer from 1 to 12, print the number of days in it in the year 2017.
```
Example input #1
1
(January)

Example output #1
31

Example input #2
2
(February)

Example output #2
28
```
```
Theory
If you don't know how to start solving this assignment, please, review a theory for this lesson:
https://snakify.org/lessons/if_then_else_conditions/

You may also try step-by-step theory chunks:
https://snakify.org/lessons/if_then_else_conditions/steps/1/
```
```
a = int(input())
if a%2 !=0 and a!=2 and a<=7:
  print("31")
elif a==2:
  print("28")
elif a<=7:
  print("30")
elif a%2==0 and a>=7:
  print("31")
else:
  print("30")
```
