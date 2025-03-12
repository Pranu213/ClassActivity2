# ClassActivity2
# README

Errors Found and Fixes Applied:

1. `def is_narc(n)` → Missing colon → `def is_narc(n):`
2. `num_str == str(n)` → `==` instead of `=` → `num_str = str(n)`
3. `num_digits == len(num_str)` → `==` instead of `=` → `num_digits = len(num_str)`
4. `sum(int(digit) *** num_digits for digit in num_str)` → `***` instead of `**` → `sum(int(digit) ** num_digits for digit in num_str)`
5. `if is_narcissistic(num)` → Incorrect function name → `if is_narc(num):`
6. `def print_narcis_numbers(start end)` → Missing comma → `def print_narcis_numbers(start, end):`
7. `for num in range(start, end + 1)` → Missing colon → `for num in range(start, end + 1):`
8. `print_narc_numbers(1000, 5000)` → Incorrect function name → `print_narcis_numbers(1000, 5000)`
