## Given two timestamps of the same day: a number of hours, minutes and seconds for both of the timestamps. The moment of the first timestamp happened before the moment of the second one. Calculate how many seconds passed between them.
```
Example input #1
1
1
1
2
2
2

Example output #1
3661

Example input #2
1
2
30
1
3
20

Example output #2
50
```
```
Theory
If you don't know how to start solving this assignment, please, review a theory for this lesson:
https://snakify.org/lessons/print_input_numbers/ 

You may also try step-by-step theory chunks:
https://snakify.org/lessons/print_input_numbers/steps/1/
```
```
a1 = int(input())
a2 = int(input())
a3 = int(input())
b1 = int(input())
b2 = int(input())
b3 = int(input())
# Print a value:
a = (a1 * 60 * 60 + a2 * 60 + a3)
#print(a)
b = (b1 * 60 * 60 + b2 * 60 + b3)
#print(b)
print(b - a)
```
