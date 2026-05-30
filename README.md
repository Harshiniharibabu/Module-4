# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

```
import math
class cse:
    def mech(self, r):
        area = math.pi * r * r
        print("Area of the circle:", area)
radius = float(input("Enter the radius of the circle: "))
obj = cse()
obj.mech(radius)
```

## Output
<img width="1919" height="1020" alt="image" src="https://github.com/user-attachments/assets/f71dcb9e-2f5c-439a-bb60-b450bc5694e6" />

## Result
Thus, the program is executed successfully.

## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
def merge(dict1, dict2):
    merged = {**dict1, **dict2}
    return merged
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'d': 4, 'e': 5, 'a': 6}
result = merge(dict1, dict2)
print("Merged dictionary:", result)
```

## Output
<img width="1919" height="1024" alt="image" src="https://github.com/user-attachments/assets/cf4dbdcb-cac5-4872-87a1-7ec5a3afe6df" />

## Result
Thus, the program is executed successfully.

# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
data = {'vehicle': 'car', 'animal': 'tiger', 'flower': 'rose', 'fruit': 'apple','vegetable': 'carrot'}
sorted_by_keys = dict(sorted(data.items()))
sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))
print("Original dictionary:", data)
print("Sorted by keys:", sorted_by_keys)
print("Sorted by values:", sorted_by_values)
```

## Sample Output
<img width="1919" height="1028" alt="image" src="https://github.com/user-attachments/assets/5da6603b-f21c-46b1-966c-22f45feb1cc2" />

## Result
Thus, the program is executed successfully.

