# Arithmetic Arranger

A Python function that takes a list of arithmetic problems (addition and subtraction only) and arranges them vertically and side-by-side, just like students do in school.

## 📌 Features

- Aligns arithmetic problems in a clean, readable vertical format.
- Supports optional solution display.
- Handles up to **five** problems at a time.
- Provides clear and informative **error messages** for invalid input.
- Fully right-aligns numbers and operators.
- Follows standard primary school vertical arrangement.

---

## 🧠 Example

```python
from arithmetic_arranger import arithmetic_arranger

print(arithmetic_arranger(["32 + 8", "1 - 3801", "9999 + 9999", "523 - 49"], True))
