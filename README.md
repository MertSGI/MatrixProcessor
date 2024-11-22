
# Matrix Processor 🧮

Matrix Processor is a Kotlin-based program that performs various operations on matrices, including addition, multiplication, transposition, determinant calculation, and inversion.

---

## 🚀 Features

- **Matrix Addition**: Add two matrices of the same dimensions.
- **Matrix Multiplication**:
  - Multiply a matrix by a constant.
  - Multiply two matrices (where dimensions are compatible).
- **Matrix Transposition**:
  - Transpose along the main diagonal.
  - Transpose along the side diagonal.
  - Transpose vertically or horizontally.
- **Determinant Calculation**: Compute the determinant of a matrix.
- **Matrix Inversion**: Find the inverse of a matrix.

---

## 🛠️ How to Use

1. **Run the Program**  
   Compile and run the program using Kotlin:
   ```bash
   kotlinc processor.kt -include-runtime -d processor.jar
   java -jar processor.jar
   ```

2. **Choose an Operation**  
   The program will present you with a menu of options:
   ```
   1. Add matrices
   2. Multiply matrix by a constant
   3. Multiply matrices
   4. Transpose matrix
   5. Calculate a determinant
   6. Inverse matrix
   0. Exit
   Your choice:
   ```

3. **Follow the Prompts**  
   Enter the required matrix dimensions and elements as prompted.

---

## 📖 Menu Options Explained

1. **Add Matrices**  
   - Enter the size and elements of two matrices.
   - Both matrices must have the same dimensions.

2. **Multiply Matrix by a Constant**  
   - Enter the size and elements of a matrix.
   - Enter a constant to multiply each element of the matrix by that constant.

3. **Multiply Matrices**  
   - Enter the size and elements of two matrices.
   - Ensure the number of columns in the first matrix equals the number of rows in the second matrix.

4. **Transpose Matrix**  
   - Choose one of the transposition methods:
     - Main diagonal
     - Side diagonal
     - Vertical line
     - Horizontal line
   - Enter the size and elements of the matrix to transpose.

5. **Calculate a Determinant**  
   - Enter the size and elements of the matrix.
   - Ensure the matrix is square.

6. **Inverse Matrix**  
   - Enter the size and elements of the matrix.
   - Ensure the matrix is square and its determinant is non-zero.

0. **Exit**  
   - Quit the program.

---

## 🧪 Example Input/Output

### Add Matrices
**Input**:
```
Enter size of first matrix: 2 2
Enter first matrix:
1 2
3 4
Enter size of second matrix: 2 2
Enter second matrix:
5 6
7 8
```

**Output**:
```
The result is:
6 8
10 12
```

### Transpose Matrix (Main Diagonal)
**Input**:
```
Enter size of matrix: 2 3
Enter matrix:
1 2 3
4 5 6
```

**Output**:
```
The result is:
1 4
2 5
3 6
```

---

## 📂 Project Structure

```
MatrixProcessor/
├── processor.kt        # Main Kotlin source code
└── README.md           # Documentation
```

---

## 🏅 Key Concepts

- **Kotlin Operator Overloading**: For intuitive matrix operations (`+`, `*`).
- **Functional Programming**: Used for transformations and concise computations.
- **Matrix Algebra**: Core mathematical operations implemented programmatically.

---

## 🛠️ Requirements

- Kotlin Compiler
- JVM (Java Virtual Machine)

---

## 📬 Contributing

Contributions are welcome! If you find any issues or have ideas for new features, feel free to create an issue or submit a pull request.

---

## 📜 License

This project is licensed under the Apache 2.0 License. See the [LICENSE](LICENSE) file for more details.

---

### Thank you for using the Matrix Processor! 😊
