# TP4 - Introduction à JavaScript
> Types simples, variables et instructions de base

---

## 📁 Project Structure

```
TP4/
├── exercice1.html       # Temperature conversion
├── exercice2.html       # Duration conversion
├── exercice2-bis.html   # Duration conversion (improved)
├── exercice3.html       # Sort 3 numbers
├── exercice4.html       # Triangle pattern
├── exercice4-bis.html   # Pyramid pattern
├── exercice5.html       # Prime number checker
├── exercice6.html       # Fibonacci sequence
└── exercice7.html       # Square root approximation
```

---

## 📝 Exercises

### Exercise 1 — Temperature Conversion (`exercice1.html`)
Converts a temperature from **Fahrenheit to Celsius** using the formula:
```
tempC = (5/9) × (tempF − 32)
```
- **Function:** `degreC()`
- **Input:** Temperature in Fahrenheit
- **Output:** Equivalent temperature in Celsius

**Example:**
```
Input  : 60.0
Output : Cette température équivaut à 15.56 degrés Celsius
```

---

### Exercise 2 — Duration Conversion (`exercice2.html`)
Converts a number of **seconds** into days, hours, minutes, and seconds.
- **Function:** `hjms()`
- **Input:** Duration in seconds
- **Output:** Equivalent in days, hours, minutes, seconds

**Example:**
```
Input  : 235789
Output : 2 jours 17 heures 29 minutes 49 secondes
```

---

### Exercise 2-bis — Improved Duration Conversion (`exercice2-bis.html`)
Same as Exercise 2 but with improved display:
- Zero values are **hidden**
- Value of `1` is displayed in **singular** (no "s")

**Example:**
```
Input  : 3621
Output : 1 heure 21 secondes
```

---

### Exercise 3 — Sort 3 Numbers (`exercice3.html`)
Reads 3 numbers and displays them in **ascending order**.
- **Function:** `troisNombres()`
- **Input:** 3 integers
- **Output:** Numbers sorted from smallest to largest

**Example:**
```
Input  : 14, 10, 17
Output : les nombres dans l'ordre croissant : 10 14 17
```

---

### Exercise 4 — Triangle Pattern (`exercice4.html`)
Displays a triangular pattern of stars of a given size.
- **Function `triangle1()`:** uses `while` loop
- **Function `triangle2()`:** uses `for` loop

**Example (size = 6):**
```
*
**
***
****
*****
******
```

---

### Exercise 4-bis — Pyramid Pattern (`exercice4-bis.html`)
Displays a **pyramid** pattern of stars of a given size.
- **Function:** `piramid()`

**Example (size = 7):**
```
      *
     ***
    *****
   *******
  *********
 ***********
*************
```

---

### Exercise 5 — Prime Number Checker (`exercice5.html`)
Tests whether a given integer is **prime or not**.
- **Function:** `premier()`
- **Input:** Positive integer
- **Output:** Whether the number is prime, and if not, its smallest divisor

**Example:**
```
Input  : 7   → 7 est un nombre premier
Input  : 25  → 25 n'est pas un nombre premier, il est divisible par 5
```

---

### Exercise 6 — Fibonacci Sequence (`exercice6.html`)
The Fibonacci sequence: `U0 = 0, U1 = 1, Un+1 = Un + Un-1`

- **`fibo1()`** — computes the **nth term** of the sequence
- **`fibo2()`** — finds the **first term greater than** a given value and its rank

**Example:**
```
Input  : 50
Output : Premier terme > 50 : u(11) = 89
```

---

### Exercise 7 — Square Root Approximation (`exercice7.html`)
Approximates **√A** using the formula:
```
U0 = A/2
Un+1 = 1/2 × (Un + A/Un)
```
Stops when `|uₙ² − A| < 0.0001`

- **Function:** `raca1()`
- **Input:** A real number between 1 and 100
- **Output:** Approximate square root

**Example:**
```
Input  : 19.23
Output : Valeur approchée de la racine carrée = 4.385202389856321
```

---

## 🚀 How to Run

1. Open any `.html` file in your browser
2. Follow the `prompt()` instructions
3. Open the **browser console** (`F12` → Console) to see the output

---

