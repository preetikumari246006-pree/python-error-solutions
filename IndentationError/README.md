# IndentationError in Python 🐍

## ❓ What is IndentationError?

IndentationError happens when spacing before code is incorrect.

Python uses indentation (spaces) to define blocks of code.
If indentation is wrong, Python will show an error.

---

## 🚫 Example of Wrong Code

```python
if True:
print("Hello")
```

This will cause:

IndentationError: expected an indented block

---

## ✅ Correct Code

```python
if True:
    print("Hello")
```

Notice the 4 spaces before `print()`.

---

## 🤔 Why This Error Happens

- Missing spaces before a statement
- Mixing tabs and spaces
- Wrong alignment inside loops or if statements

---

## 🛠 How to Fix It

1. Use **4 spaces** for indentation
2. Do NOT mix tabs and spaces
3. In VS Code:
   - Look at bottom right corner
   - Make sure it says **Spaces: 4**
   - Convert indentation to spaces if needed

---

## 💡 My Experience

I faced this error while building my first Python project.
The problem was missing indentation inside an if statement.

After fixing spacing, the code worked perfectly.

---

## 🎯 Tip for Beginners

Always check indentation carefully when you see this error.
In Python, spacing is very important.
