# # ➖ Matrix Operations-Matrix Subtraction in Python

## 🎯 AIM:
To write a Python program that reads two matrices from the user and performs matrix subtraction.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` for rows and columns
3. Get the values of `r` and `c` from the user
4. Define a function `create_matrix(n, m)` to:
   - Prompt user for each matrix element
   - Append each row to form a complete matrix
5. Call the `create_matrix()` function twice to read two matrices `A` and `B`
6. Define a loop to subtract the elements of matrix `B` from matrix `A`
7. Store the result in a new matrix `C`
8. Print the resulting matrix `C`
9. **Stop**

---

## 💻 PROGRAM:
```
def create_matrix(r, c):
    print(f"Enter elements for a {r}x{c} matrix:")
    return [[int(input(f"Element [{i+1}][{j+1}]: ")) for j in range(c)] for i in range(r)]

r = int(input("Enter number of rows: "))
c = int(input("Enter number of columns: "))

print("\nMatrix A:")
A = create_matrix(r, c)

print("\nMatrix B:")
B = create_matrix(r, c)

C = [[A[i][j] - B[i][j] for j in range(c)] for i in range(r)]

print("\nResultant Matrix (A - B):")
for row in C:
    print(row)
```
## OUTPUT:
<img width="1538" height="814" alt="image" src="https://github.com/user-attachments/assets/e3f51658-3980-4583-adb0-c50ba80cfad2" />

## RESULT:
Therefore the given Python Program has been executed successfully and the output has been verified.
