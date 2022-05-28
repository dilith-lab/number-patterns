# number-patterns
Under construction! 
Not ready for use yet. Currently experimenting and planning.
Developed by Dilith Achalan (c) 2022


## Summary
This project is created to identify the number patterns on a given number sequence which will get the difference in sequence and general term or general ratio.

### How to import the module
You can import ***numpatt*** module which is inside ***numpatterns*** project folder. You may use below code snippet to import ***convert_str_float*** funtion.

```python
from numpatterns.numpatt import convert_str_float
```
Below functions are available to use. 
**Funtions**
- convert_str_float
- check_list
- get_common_term
- get_common_ratio
- common_difference
- multi_difference
- classify_pattern

### Examples of how to use
#### convert_str_float - funtion
This funtion take two parameters **string number list**, **seperator** and return the output as a list with floating values.

```python
# get user input to enter a number sequence
num_list = input("Enter the number sequence: ")
nth = int(input("Enter the nth in sequence: "))

# calling the 'convert_str_float' function to get a list with string values to float
n_list = convert_str_float(num_list, sep=",")
print(n_list)
```

#### check_list - funtion
This funtion will take **string number list** and check if the list has at least two items to operate sequence

```python
n_list = [2, 4, 6, 8]

# calling the 'check_list' function to validate if list has at least two items
if check_list(n_list):
    print("This list has at least two items ")
```