## JugsMugsPugs Plus
Write a program that receives a number on the input.

  - If the number is a multiple of 3, or it contains digit 3, it prints "Jugs". 
  - If the number is a multiple of 5, or it contains digit 5, it prints "Mugs".
  - If the number is a multiple of 7, or it contains digit 7, it prints "Pugs".

Otherwise, it prints the number.
```
SPECIAL REQUIREMENT: 
Try and limit the number of conditional statements to not more than 4. 
And use only one print statement.
```
```
INPUT 
73 
OUTPUT
JugsPugs

INPUT 
51  

OUTPUT
JugsMugs


INPUT 
105

OUTPUT 
JugsMugsPugs
```
```
b = input()
a = int(b)
print (str("Jugs" if ((a%3==0)or('3'in b)) else '')+str("Mugs" if ((a%5==0)or('5'in b)) else '')+str("Pugs" if ((a%7==0)or('7'in b)) else '') if (((a%3==0)or('3'in b)) or ((a%5==0)or('5'in b)) or ((a%7==0)or('7'in b))) else a)
```
