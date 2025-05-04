# 🔐 Password Generator

A simple and customizable password generator written in Python. This script creates secure passwords using lowercase letters, numbers, and uppercase characters to help you stay protected online.

## 📌 Features

- Generate multiple passwords at once
- Randomly inserts numbers and capital letters for better complexity
- Customizable password lengths

## 🧠 How It Works

1. A base password is generated using random lowercase letters.
2. Some letters are replaced with numbers at random positions.
3. A few letters are capitalized at random to improve strength.

### Example

```python
>>> generatePassword([8, 10, 12])
['b5mUwqaz', 'q2lMbvXeRa', 'nm3xDytPrEwQ']
