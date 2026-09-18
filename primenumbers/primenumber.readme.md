# Java Prime Number Checker

A simple Java program that checks whether a given number is a **Prime Number**.

## 📌 What is a Prime Number?

A prime number is a natural number greater than 1 that has exactly two factors:

* 1
* The number itself

### Examples

```text
2  → Prime
3  → Prime
5  → Prime
7  → Prime
11 → Prime
13 → Prime

4  → Not a Prime Number
6  → Not a Prime Number
8  → Not a Prime Number
9  → Not a Prime Number
10 → Not a Prime Number
```

## 📂 Project Structure

```text
java-prime-number/
├── .gitignore
├── PrimeNumber.java
└── README.md
```

## 💻 Program

The program accepts a number from the user and checks whether the number is divisible by any number other than 1 and itself.

The program checks possible factors up to the square root of the number.

If a factor is found, the number is not prime.

## ⚙️ Working Principle

The program follows these steps:

```text
1. Read a number from the user.
2. Check if the number is less than or equal to 1.
3. If yes, it is not prime.
4. Otherwise, check divisibility from 2 to √n.
5. If the number is divisible by any value, it is not prime.
6. Otherwise, it is a prime number.
```

## ▶️ How to Run

### Step 1: Check Java

```bash
java --version
```

### Step 2: Check Java Compiler

```bash
javac --version
```

### Step 3: Compile

```bash
javac PrimeNumber.java
```

### Step 4: Run

```bash
java PrimeNumber
```

## 📊 Sample Output

### Example 1 — Prime Number

```text
Enter a number: 17
17 is a Prime Number.
```

### Example 2 — Not a Prime Number

```text
Enter a number: 20
20 is not a Prime Number.
```

### Example 3 — Prime Number

```text
Enter a number: 29
29 is a Prime Number.
```

### Example 4 — Number less than 2

```text
Enter a number: 1
1 is not a Prime Number.
```

## 🧠 Concepts Used

* Java
* Scanner
* User input
* Variables
* Boolean variables
* For loop
* If-else statement
* Break statement
* Modulus operator `%`
* Conditional logic

## ⏱️ Complexity

**Time Complexity:** `O(√n)`

**Space Complexity:** `O(1)`

The program checks possible factors only up to the square root of the input number.

## 🚀 Future Improvements

This project can be extended to:

* Print all prime numbers within a range
* Find the first N prime numbers
* Check multiple numbers
* Create a separate method for prime checking
* Create a menu-driven prime number application
* Generate prime numbers using the Sieve of Eratosthenes

## 🛠️ Technologies

* Java
* Git
* GitHub

## 👨‍💻 Author

**Your Name**

GitHub: `https://github.com/your-username`

---

⭐ If you found this project useful, consider giving the repository a star!

```
```