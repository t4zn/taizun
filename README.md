
# taizun

A simple Python utility library containing basic functions such as string reversal, number-to-words conversion, basic arithmetic operations, and more.

## Functions

### reverse(s)

Reverses the input string `s`.

### number_to_words(num)

Converts a number to its word equivalent.

### calculator(a, b, operation)

Performs basic arithmetic operations like add, subtract, multiply, and divide on `a` and `b`.

### greet(name)

Returns a personalized greeting message.

### square(num)

Returns the square of a number.

### cube(num)

Returns the cube of a number.

### factorial(n)

Returns the factorial of a number.

### power(base, exp)

Calculates the result of base raised to the power of exp.

### min_val(a, b)

Returns the smaller of two numbers.

### max_val(a, b)

Returns the larger of two numbers.

### avg(nums)

Returns the average of a list of numbers.

### is_palindrome(s)

Checks if a string is a palindrome (reads the same backward and forward).

### is_prime(n)

Checks if a number is prime.

### factorial_list(nums)

Returns a list of factorials for each number in the input list.

### get_length(s)

Returns the length of a string.

### capitalize(s)

Capitalizes the first letter of the string.

### lowercase(s)

Converts a string to lowercase.

### uppercase(s)

Converts a string to uppercase.

### concat(s1, s2)

Concatenates two strings.

### strip_spaces(s)

Removes leading and trailing spaces from a string.

### split_string(s, delimiter)

Splits a string by the given delimiter and returns a list.

### join_list(lst, delimiter)

Joins a list of strings into a single string using the given delimiter.

### convert_to_int(s)

Converts a string to an integer (returns None if conversion fails).

### convert_to_float(s)

Converts a string to a float (returns None if conversion fails).

### check_type(val)

Returns the type of the given value as a string.

### remove_duplicates(lst)

Removes duplicates from a list.

### merge_lists(lst1, lst2)

Merges two lists into one.

### reverse_list(lst)

Reverses the order of elements in a list.

### sort_list(lst)

Sorts a list in ascending order.

### flatten_list(nested_lst)

Flattens a nested list into a single list.

### count_occurrences(lst, val)

Counts the number of occurrences of a value in a list.

### extract_numbers(s)

Extracts all numbers from a string and returns them as a list of integers.

## Example Usage:

```python
import taizun as tz

# Reverse a string
st = "hello"
print(tz.reverse(st))  # Output: "olleh"

# Number to words
print(tz.number_to_words(5))  # Output: "five"

# Calculator
print(tz.calculator(10, 5, 'add'))  # Output: 15
print(tz.calculator(10, 5, 'subtract'))  # Output: 5
print(tz.calculator(10, 5, 'multiply'))  # Output: 50
print(tz.calculator(10, 5, 'divide'))  # Output: 2.0

# Greeting
print(tz.greet("Alice"))  # Output: "Hello, Alice!"

# Square a number
print(tz.square(4))  # Output: 16

# Cube a number
print(tz.cube(3))  # Output: 27

# Check if a string is a palindrome
print(tz.is_palindrome("madam"))  # Output: True

# Check if a number is prime
print(tz.is_prime(7))  # Output: True

# Get length of a string
print(tz.get_length("Hello World"))  # Output: 11

# Capitalize a string
print(tz.capitalize("hello"))  # Output: "Hello"

# Convert a string to lowercase
print(tz.lowercase("HELLO"))  # Output: "hello"

# Merge two lists
lst1 = [1, 2, 3]
lst2 = [4, 5, 6]
print(tz.merge_lists(lst1, lst2))  # Output: [1, 2, 3, 4, 5, 6]
```
