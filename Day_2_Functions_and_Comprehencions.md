#                                                                """ TYPES OF COMPREHENCIONS """
## 1)List Comprehencion

```python
# Simple list
list_of_numbers = []
for i in range(10, 100):
    if i % 2 == 0:
        list_of_numbers.append(i)
print(list_of_numbers)

# With list comprehension
list_of_numbers = [i for i in range(10, 100) if i % 2 == 0]
print(list_of_numbers)
```
## 2)Set Comprehencion

```python
# Simple set
text = "Hello world hello"
words = set()

for word in text.split():
    words.add(word)

# With set comprehension
text = "Hello world hello"
words = {word.lower() for word in text.split()}
print(words)
```

## 3)Dictionary Comprehencion

```python
dict_ = {
    "A": "hwieufy2ihfoa;iwyr9haer7qw3",
    "B": "ir32gkahjcs7r8t2835ruiagf7832r",
    "C": "273s"
}

# With simple dict
result = {}
for i, j in dict_.items():
    result[i] = len(j)

print(result)

# With dict comprehension
result = {i: len(j) for i, j in dict_.items()}
print(result)
```
_______________________________________________________________
#                                                                """ Practice work (Functions) """
1)Convertation Celsium to Fahrenheit and Fahrenheit to Celsium
```python
def convert_celsius_to_fahrenheit(a):
    b = ( a * 9/5) + 32
    return  b
def convert_fahrenheit_to_celsius(a):
    b = (a - 32) * 5/9
    return b

Degree = int(input("Give a degree: "))
print("Choose an option(1 , 2):")
print("1. Convert C to F")
print("2. Convert F to C")
choice = int(input("Option: "))
if choice == 1:
    print(convert_celsius_to_fahrenheit(Degree))
elif choice == 2:
    print(convert_fahrenheit_to_celsius(Degree))
else:
    print("ERROR")
    print("You did something wrong!")
    print("Please< try again.")
```
2)Write a function called check-season, it takes a month parameter and returns the season: Autumn, Winter, Spring or Summer
```python
def Check_Season(month):
    if month in ["June", "July", "August"]:
        return "Summer"
    elif month in ("December", "January", "February"):
        return "Winter"
    elif month in ["March", "April", "May"]:
        return "Spring"
    elif month in ["September", "October", "November"]:
        return "Autumn"
    else:
        return "You entered a wrong month. Please try again(example: June)"

part_of_season = str(input("Enter a month: "))
print(Check_Season(part_of_season))
```
