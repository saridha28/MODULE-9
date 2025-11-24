# 🧾 List Comprehension:Generates all even numbers between 200 and 300
## 🎯 AIM:
To write a Python class-based program that generates all even numbers between 200 and 300 using **list comprehension**, and stores them in a list.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a class named `program`
3. Create variables `a`, `b`, and `c` to represent:
   - `a`: Lower limit
   - `b`: Step value
   - `c`: Upper limit
4. Initialize the values using a constructor `__init__`
5. Define a method `display()` that uses **list comprehension** to store even numbers
6. Print the resulting list of even numbers
7. **Stop**

---

## 💻 PROGRAM:
```
class program:
    def __init__(self):
        self.a = 200
        self.b = 2
        self.c = 300

    def display(self):
        even_numbers = [i for i in range(self.a, self.c + 1) if i % self.b == 0]
        print("Even numbers between 200 and 300:", even_numbers)

obj = program()
obj.display()
```

## OUTPUT:
<img width="1681" height="861" alt="image" src="https://github.com/user-attachments/assets/5dc7f6ad-e446-4a98-b3b5-f573c97e8516" />

## RESULT:
Therefore the given Python Program has been executed successfully and the output has been verified.
