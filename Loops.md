1) "This algorithm shows sum of integers from num1 to num2"
```python
num1 = int(input("from integer : "))
num2 = int(input("to integer : "))
d = 0
for i in range(num1, num2+1):
  d += i
print('sum of integers from ', num1 , ' to ', num2,' is equal to ', d)

"This algorithm shows sum of integers from num1 to num2"
```
-----------------------------------------------------------------------
2) "This algroithm for finding Fibonachi number!"
```python
num1 = 0
num2 = 1
integer = int(input(" iterrations time : "))
sum = 0
for i in range(integer):
    num3 = num2 + num1
    num1 = num2
    num2 = num3
    print(num3)
```
-----------------------------------------------------------------------
3) "Even number print!"
```python
for i in range(0, 102, 2):  #from 0 to 102 with interval 2
    print(i)
```
4) "Odd number print!"
```python
for i in range(1, 101, 2):   #from 1 to 101 with interval 2
    print(i)
```
-----------------------------------------------------------------------
5) "Multiplication Table from 2 to 10!"
```python
num_1 = 2
num_2 = 2

for i  in range(8):   #Here is 8 because 10-2(number from what we start(num_1)) = 8
    for j in range(8):    #Here is 8 because 10-2(number from what we start(num_2)) = 8
        print(num_1,'*',num_2,'=',num_1*num_2)
        num_2 += 1
    print('==========')
    num_1 += 1
    num_2 = 2
```
6) "Power of Number!"
```python
number = int(input("number: "))
number_1 = number
power = int(input("power:"))  
for i in range(power-1):   #power - 1 to make a correct calculations! 
    number *= number_1
    print(number)
print('number ',number_1, ' in power ', power,'will be: ',number)
```
7)Shapes!
```python
num = int(input("number of shelves: "))
a = num + 1
for i in range(a):      #increasing triangle
    print(i * "*")
print("<==============>")
for i in range(a):
    print(a * "*")    #rectangle
print("<==============>")
for i in range(num):
    print((num) * "* ")    #square
print("<==============>")
while a > 0:
    print(a * "*")      #decreasing triangle
    a -= 1

```
8) Alternative Shapes!
```python
num = int(input("number of shelves: "))
a = num
b = 0
inital = b


while a > 0:                   #Alternative decreasing triangle
    print(b * " ", a * "*") 
    b += 1
    a -= 1
a = num
b = inital
print("<==============>")
for i in range(a):          #Alternative increasing triangle
    print(a * " ", b * "*") 
    b += 1
    a -= 1
```
