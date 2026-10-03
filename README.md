# Even and Odd Number Checker

A simple Python program that accepts a number and determines whether it is even or odd.

## Objective

Learn conditional statements (`if` / `else`) and the modulus operator (`%`).

## Tools Used

- Python 3

## How It Works

The program takes a number as input and checks the remainder when it is divided by 2:

- If `number % 2 == 0`, the number is **Even**.
- Otherwise, the number is **Odd**.

Negative numbers are handled correctly because Python's `%` operator returns the right remainder for them too (e.g., `-9 % 2` is `1`, `-4 % 2` is `0`).

## Code

```python
number = int(input("Enter a number: "))

if number % 2 == 0:
    print(number, "is Even")
else:
    print(number, "is Odd")
```

## How to Run

1. Make sure Python 3 is installed.
2. Save the code in a file named `evenOdd.py`.
3. Run it from the terminal:

```bash
python evenOdd.py
```

## Example Output

```
Enter a number: 10
10 is Even

Enter a number: 7
7 is Odd

Enter a number: -4
-4 is Even

Enter a number: -9
-9 is Odd

Enter a number: 0
0 is Even
```

## Concepts Learned

- Taking user input with `input()`
- Converting input to an integer with `int()`
- Using the modulus operator `%`
- Using `if` / `else` conditional statements

## Author

Nabila khan