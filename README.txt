# Count Vowels and Consonants in Python

## Description
This project is a simple Python program that counts the number of vowels and consonants in a given string.

## Features
- Takes user input.
- Counts vowels (a, e, i, o, u).
- Counts consonants (b-z except vowels).
- Ignores spaces, numbers, and special characters.
- Displays the final count.

## Python Program
```python
s = input("Enter a string: ")

vowels = 0
consonants = 0

for ch in s.lower():
    if ch.isalpha():
        if ch in "aeiou":
            vowels += 1
        else:
            consonants += 1

print("Vowels:", vowels)
print("Consonants:", consonants)
```

## Example

**Input:**
```text
Hello World
```

**Output:**
```text
Vowels: 3
Consonants: 7
```

## Technologies Used
- Python 3

## Learning Outcomes
- String handling
- For loops
- If-else conditions
- Character checking
- Counting techniques

## Author
Sashank Gotte
