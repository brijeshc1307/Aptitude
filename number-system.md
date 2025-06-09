## **Number System – Formulas and Shortcuts**

---

### **1. Basics**

* **Natural Numbers**: Counting numbers → 1, 2, 3, 4, ...
* **Whole Numbers**: Natural numbers + 0 → 0, 1, 2, 3, ...
* **Integers**: Includes positive and negative whole numbers.
* **Even Numbers**: Divisible by 2 → 2, 4, 6, ...
* **Odd Numbers**: Not divisible by 2 → 1, 3, 5, ...

---

### **2. Divisibility Rules (Shortcuts)**

| Number | Divisibility Rule                                            |
| ------ | ------------------------------------------------------------ |
| 2      | Last digit is even (0, 2, 4, 6, 8)                           |
| 3      | Sum of digits divisible by 3                                 |
| 4      | Last 2 digits divisible by 4                                 |
| 5      | Ends in 0 or 5                                               |
| 6      | Divisible by both 2 and 3                                    |
| 7      | Double last digit, subtract from rest, result divisible by 7 |
| 8      | Last 3 digits divisible by 8                                 |
| 9      | Sum of digits divisible by 9                                 |
| 10     | Ends in 0                                                    |
| 11     | Alternating sum of digits divisible by 11                    |

---

### **3. HCF and LCM**

* **HCF (GCD)**: Highest common factor.
* **LCM**: Least common multiple.

**Relation**:

```
HCF × LCM = Product of Two Numbers
```

---

### **4. Remainder Theorem (Shortcuts)**

* **a % b = r** → Remainder when **a** is divided by **b**
* **(a × b) % c = \[(a % c) × (b % c)] % c**
* **(a + b) % c = \[(a % c) + (b % c)] % c**
* **(a - b) % c = \[(a % c) - (b % c)] % c**

**Special Case**:

```
Remainder when 10^n is divided by 9 is always 1.
```

---

### **5. Number of Zeros at the End**

**Trailing Zeros in Factorial (n!)**:

```
= ⌊n/5⌋ + ⌊n/25⌋ + ⌊n/125⌋ + ...
```

---

### **6. Unit Digit Tricks**

**For Powers (a^b):**

* Identify the cyclicity of the unit digit of a.
* Find b mod cycle length.

Example:

```
Unit digit of 7^67
Cycle: 7, 9, 3, 1 → length 4
67 % 4 = 3 → Third element = 3
Answer: 3
```

---

### **7. Types of Numbers**

* **Perfect Number**: Sum of its proper divisors equals the number (e.g., 6, 28).
* **Prime Number**: Only divisible by 1 and itself.
* **Co-prime**: Two numbers with HCF = 1.
* **Composite Number**: Not prime; has more than two factors.

---

### **8. Sum and Count Formulas**

| Type                                      | Formula                           |
| ----------------------------------------- | --------------------------------- |
| Sum of first n natural numbers            | $\frac{n(n+1)}{2}$                |
| Sum of first n even numbers               | $n(n+1)$                          |
| Sum of first n odd numbers                | $n^2$                             |
| Sum of squares of first n natural numbers | $\frac{n(n+1)(2n+1)}{6}$          |
| Sum of cubes of first n natural numbers   | $\left[\frac{n(n+1)}{2}\right]^2$ |

---

### **9. Digit-Based Problems**

**Sum of digits of a number**: Keep adding digits until you reach a single digit.
Used in digital root, cyclicity, and divisibility.

**Digital Root Shortcut**:

```
Digital Root of n = 1 + ((n - 1) % 9)
```

---

### **10. Miscellaneous Shortcuts**

* **Product of n consecutive numbers is divisible by n!**
* If a number is divisible by both **a** and **b**, then it's divisible by **LCM(a, b)**.
* For any integer **n**:

  ```
  (n^2 – 1) is divisible by 8 if n is odd.
  ```

---

## Tips to Solve Fast

1. Memorize divisibility rules.
2. Use HCF × LCM = product for quick calculation.
3. Remember power cycles for unit digit.
4. Use digital root for quick checking.

---

---

### 🔢 **1. Divisibility Rule Example**

**Q.** Is 738 divisible by 3?
**A.** Sum of digits = 7 + 3 + 8 = 18 → 18 is divisible by 3
✅ **Yes, 738 is divisible by 3**

---

### 🧮 **2. HCF and LCM**

**Q.** Find HCF and LCM of 12 and 18.
**A.**

* Factors of 12: 1, 2, 3, 4, 6, 12
* Factors of 18: 1, 2, 3, 6, 9, 18
* HCF = 6
* LCM = (12 × 18) / 6 = 216 / 6 = 36
  ✅ **HCF = 6, LCM = 36**

---

### 🔁 **3. Remainder Rule**

**Q.** Find remainder when (28 × 37) is divided by 5.
**A.**

* 28 % 5 = 3, 37 % 5 = 2
* (3 × 2) % 5 = 6 % 5 = **1**
  ✅ **Remainder = 1**

---

### 🧠 **4. Trailing Zeros**

**Q.** How many zeros are at the end of 100!
**A.**
100 ÷ 5 = 20, 100 ÷ 25 = 4
→ Total zeros = 20 + 4 = **24**
✅ **Answer: 24 zeros**

---

### 🧰 **5. Unit Digit of Power**

**Q.** What is the unit digit of 7^45?
**A.**
Cycle of 7: 7, 9, 3, 1 → Length = 4
45 % 4 = 1 → First element = 7
✅ **Unit digit = 7**

---

### 🔣 **6. Perfect Number**

**Q.** Is 28 a perfect number?
**A.** Divisors of 28 (excluding 28) = 1 + 2 + 4 + 7 + 14 = 28
✅ **Yes, 28 is a perfect number**

---

### 🔄 **7. Sum of Natural Numbers**

**Q.** Find the sum of first 10 natural numbers.
**A.**
\= 10 × (10 + 1) / 2 = 55
✅ **Answer: 55**

---

### 🧾 **8. Digital Root**

**Q.** Find the digital root of 9876
**A.**
9 + 8 + 7 + 6 = 30 → 3 + 0 = 3
✅ **Digital Root = 3**

---

### 📌 **9. Special Trick**

**Q.** Prove that 25² – 1 is divisible by 8
**A.**
25² – 1 = 625 – 1 = 624
624 ÷ 8 = 78
✅ **Yes, it is divisible by 8**

---


