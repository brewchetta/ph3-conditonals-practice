# Python Conditionals Practice

Here are a few practice exercises testing your knowledge on conditionals (if / else statements).

Each function will require you to return True or False depending on what the input for that function was.

There are *no tests* which means you'll have to test this code yourself. You can run different test cases with `python -i index.py` and then calling the different functions like they're being called in the examples below...

## Exercises

`is_a_string()` - Returns True if the argument is a string and False if not

Examples:
```python
is_a_string("I am a string") # --> True
is_a_string(1337) # --> False
```

`has_peanut_butter()` - Accepts a list as an argument and returns True if the ingredients include `"peanut butter"` and False if 

Examples:
```python
has_peanut_butter(['bread', 'ham', 'cheese', 'peanut butter']) # --> True
has_peanut_butter(['bread', 'lettuce', 'tomato', 'mustard', 'strawberry jam']) # --> False
```

`has_allergen()` - Accepts two arguments, ingredients_list which is a list of ingredients and allergen which is a string representing an allergen, returns True if the allergen is present and False if not

Examples:
```python
has_allergen(['bread', 'ham', 'cheese', 'peanut butter'], "bread") # --> True
has_allergen(['taco shell', 'ham', 'cheese', 'peanut butter'], "bread") # --> False
```

`stoplight()` - Accepts a color and returns `"GO"` if the color is `"green"`, `"SLOW"` if the color is `"yellow"`, `"STOP"` if the color is `"red"`, and `"OH NO"` if the color is any other color
    - As a bonus, the color arguments can be accepted as upper cased or lower cased

Examples:
```python
stoplight("green") # --> "GO"
stoplight("RED") # --> "STOP"
stoplight("aquamarine") # --> "OH NO"
```

`average()` - Accepts a list of numbers and returns the average, returns 0 if the list has nothing inside of it

Examples:
```python
average([1,2,3]) # --> 2
average([5, 10, 15, 20]) # --> 12.5
average([]) # --> 0
```

`fizz_buzz()` - Accepts a number as an argument and returns `"fizz"` if the number is divisible by 3, `"buzz"` if divisible by 5, `"fizzbuzz"` if divisible by both 3 and 5, and `None` if divisible by neither

Examples:
```python
fizz_buzz(6) # --> "fizz"
fizz_buzz(10) # --> "buzz"
fizz_buzz(30) # --> "fizzbuzz"
fizz_buzz(31) # --> None
```

`vampire_or_werewolf()` - Accepts a list of allergens, if the allergen list includes `"garlic"` or `"sunlight"` then return `"vampire"`, if the allergen list includes `"wolfsbane"` or `"silver"` then return `"werewolf"` and if neither then return `"human"`, if someone is both a vampire and a werewolf return `"werepire"`

Examples:
```python
vampire_or_werewolf(['fish', 'peanut butter', 'garlic']) # --> "vampire"
vampire_or_werewolf(['silver', 'mango']) # --> "werewolf"
vampire_or_werewolf(['gluten']) # --> "human"
vampire_or_werewolf(['wolfsbane', 'sunlight']) # --> "werepire"
```