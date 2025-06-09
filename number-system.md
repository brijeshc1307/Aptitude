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

###  **1. Divisibility Rule Example**

**Q.** Is 738 divisible by 3?
**A.** Sum of digits = 7 + 3 + 8 = 18 → 18 is divisible by 3
 **Yes, 738 is divisible by 3**

---

###  **2. HCF and LCM**

**Q.** Find HCF and LCM of 12 and 18.
**A.**

* Factors of 12: 1, 2, 3, 4, 6, 12
* Factors of 18: 1, 2, 3, 6, 9, 18
* HCF = 6
* LCM = (12 × 18) / 6 = 216 / 6 = 36
   **HCF = 6, LCM = 36**

---

###  **3. Remainder Rule**

**Q.** Find remainder when (28 × 37) is divided by 5.
**A.**

* 28 % 5 = 3, 37 % 5 = 2
* (3 × 2) % 5 = 6 % 5 = **1**
   **Remainder = 1**

---

###  **4. Trailing Zeros**

**Q.** How many zeros are at the end of 100!
**A.**
100 ÷ 5 = 20, 100 ÷ 25 = 4
→ Total zeros = 20 + 4 = **24**
 **Answer: 24 zeros**

---

###  **5. Unit Digit of Power**

**Q.** What is the unit digit of 7^45?
**A.**
Cycle of 7: 7, 9, 3, 1 → Length = 4
45 % 4 = 1 → First element = 7
 **Unit digit = 7**

---

###  **6. Perfect Number**

**Q.** Is 28 a perfect number?
**A.** Divisors of 28 (excluding 28) = 1 + 2 + 4 + 7 + 14 = 28
 **Yes, 28 is a perfect number**

---

### 🔄 **7. Sum of Natural Numbers**

**Q.** Find the sum of first 10 natural numbers.
**A.**
\= 10 × (10 + 1) / 2 = 55
**Answer: 55**

---

### 🧾 **8. Digital Root**

**Q.** Find the digital root of 9876
**A.**
9 + 8 + 7 + 6 = 30 → 3 + 0 = 3
**Digital Root = 3**

---

### **9. Special Trick**

**Q.** Prove that 25² – 1 is divisible by 8
**A.**
25² – 1 = 625 – 1 = 624
624 ÷ 8 = 78
 **Yes, it is divisible by 8**

---

Here are **25 most asked interview questions** from the **Number System** topic for **IT placements**, along with their **answers**. These are useful for companies like **TCS, Infosys, Wipro, Cognizant, Capgemini, Accenture**, etc.

---

## **Number System – 25 Interview Questions with Answers**

---

### **1. What is a prime number?**

**A.** A number greater than 1 that has only two factors: 1 and itself.

---

### **2. What is the difference between prime and co-prime?**

**A.**

* **Prime:** A single number with only two factors.
* **Co-prime:** Two numbers whose HCF is 1 (e.g., 8 and 15).

---

### **3. What is the HCF of 60 and 75?**

**A.**
60 = 2² × 3 × 5
75 = 3 × 5²
HCF = 3 × 5 = **15**

---

### **4. What is the LCM of 12 and 18?**

**A.**
LCM = (12 × 18) / HCF(12,18) = 216 / 6 = **36**

---

### **5. What is the unit digit of 6^25?**

**A.**
6^n always ends with **6**, so answer = **6**

---

### **6. Find the number of zeros at the end of 100!**

**A.**
100/5 + 100/25 = 20 + 4 = **24**

---

### **7. Find remainder when 28 × 37 is divided by 5.**

**A.**
(28 % 5 = 3, 37 % 5 = 2) → 3 × 2 = 6 → 6 % 5 = **1**

---

### **8. Is 1729 a special number?**

**A.**
Yes, it's a **Hardy-Ramanujan Number**:
1729 = 10³ + 9³ = 12³ + 1³

---

### **9. What is a perfect number? Give an example.**

**A.**
A number equal to the sum of its proper divisors.
Example: 28 (1+2+4+7+14 = 28)

---

### **10. Find digital root of 9876.**

**A.** 9+8+7+6 = 30 → 3+0 = **3**

---

### **11. What is the sum of first 20 natural numbers?**

**A.**
n(n+1)/2 = 20×21/2 = **210**

---

### **12. How many 2-digit numbers are divisible by 7?**

**A.**
Range: 14 to 98
⇒ (98–14)/7 + 1 = 85/7 + 1 = 12 + 1 = **13**

---

### **13. If a number leaves remainder 1 when divided by 2, 3, and 4, what is the number?**

**A.**
LCM(2,3,4) = 12 → Required number = 12k + 1
Smallest = **13**

---

### **14. Find the smallest number divisible by 5, 6, 7, and 8.**

**A.**
LCM(5,6,7,8) = **840**

---

### **15. If a number is divisible by 9, what can you say about its digits?**

**A.**
Sum of digits is divisible by 9.

---

### **16. Is 145 a strong number?**

**A.**
Yes, 1! + 4! + 5! = 1 + 24 + 120 = **145**

---

### **17. How many 3-digit numbers are divisible by 13?**

**A.**
Range: 104 to 999
(999 – 104)/13 + 1 = (895)/13 + 1 = 68 + 1 = **69**

---

### **18. Find HCF of 54 and 72 using prime factorization.**

**A.**
54 = 2 × 3³, 72 = 2³ × 3² → HCF = 2 × 3² = **18**

---

### **19. What is the unit digit of 9^99?**

**A.**
Cycle of 9 = 9, 1 → 99 % 2 = 1 → **9**

---

### **20. What is the LCM of 24, 36, and 60?**

**A.**
Prime factorizations:
24 = 2³×3
36 = 2²×3²
60 = 2²×3×5
LCM = 2³×3²×5 = **360**

---

### **21. What is co-prime to 35 below 50?**

**A.**
35 = 5 × 7, so exclude multiples of 5 and 7
Co-primes < 50: 1, 2, 3, 4, 6, 8, ... etc.

---

### **22. Find sum of squares of first 5 numbers.**

**A.**
n(n+1)(2n+1)/6 = 5×6×11/6 = **55**

---

### **23. What is the product of first 3 odd numbers?**

**A.** 1 × 3 × 5 = **15**

---

### **24. Find smallest number which leaves remainder 1 on dividing by 2, 3, 4, 5.**

**A.**
LCM = 60 → Required number = 60 + 1 = **61**

---

### **25. What is the sum of cubes of first 4 natural numbers?**

**A.**
\[4(4+1)/2]² = \[20/2]² = 10² = **100**

---


