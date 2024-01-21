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
for i in range(0, 102, 2):
    print(i)
```
4) "Odd number print!"
```python
for i in range(1, 101, 2):
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
