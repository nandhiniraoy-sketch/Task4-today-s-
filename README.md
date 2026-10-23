# Task4-todayDay 4 -- Python Functions

## Objective

Learn to create reusable Python functions using `def`, parameters, and
`return`.

## Tools

- 
-   Jupyter Notebook

## Programs

### 1. Addition

``` python
def add(a, b):
    return a + b

print(add(10, 20))
```

### 2. Maximum

``` python
def maximum(a, b):
    if a > b:
        return a
    return b

print(maximum(50, 80))
```

### 3. Minimum

``` python
def minimum(a, b):
    if a < b:
        return a
    return b

print(minimum(50, 80))
```

### 4. Percentage

``` python
def percentage(obtained, total):
    return (obtained / total) * 100

print(percentage(450, 500))
```

### 5. Mean (Average)

``` python
def mean(numbers):
    return sum(numbers) / len(numbers)

marks = [80, 75, 90, 95, 85]
print(mean(marks))
```

## Parameter Example

``` python
def greet(name):
    return "Hello " + name

print(greet("Jessie"))
```

## Return Example

``` python
def square(n):
    return n * n

print(square(5))
