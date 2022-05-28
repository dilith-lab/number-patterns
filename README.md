# number-patterns
Under construction! 
Not ready for use yet. Currently experimenting and planning.
Developed by Dilith Achalan (c) 2022


## Summary
This project is created to identify the number patterns on a given number sequence which will get the difference in sequence and general term or general ratio.

### Examples of How To Use
```python
from numpatterns.numpatt import convert_str_float

# get user input to enter a number sequence
num_list = input("Enter the number sequence: ")
nth = int(input("Enter the nth in sequence: "))

# calling the 'convert_str_float' function to get a list with string values to float
n_list = convert_str_float(num_list, sep=",")
print(n_list)

```