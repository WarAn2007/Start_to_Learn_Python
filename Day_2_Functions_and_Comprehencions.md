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
#                                                                """ Practice work """
