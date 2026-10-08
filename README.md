Python Concepts Used

 1. User Input

The program uses `input()` to ask the user for the price and quantity.

 2. Data Conversion

Since `input()` returns text, the program converts the values into numbers:

- `float()` is used for the price.
- `int()` is used for the quantity.

3. Calculation

The program multiplies the price by the quantity to calculate the total:

```python
total = price * quantity
```

 4. F-string

An f-string is used to display the final result in a friendly format:

```python
print(f"{quantity} items at {price:.2f} each = {total:.2f}")
```

Example Output

```text
Enter the price of one item: 50
Enter the quantity: 3
3 items at 50.00 each = 150.00
```

 Files

- `bill_calculator.py` - Contains the Python program.
- `README.md` - Explains the project and the Python concepts used.

## Conclusion

This project helped me practice taking user input, converting data types, performing calculations, and using f-strings to display a neat result.
