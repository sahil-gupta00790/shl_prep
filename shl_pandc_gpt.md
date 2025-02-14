# Probability and Permutation & Combination Problems with Solutions

## **Probability Problems**

### **1. A fair six-sided die is rolled twice. What is the probability that the sum of the two rolls is at least 10?**  
**Solution:** The possible outcomes where the sum is at least 10:  
- (4,6), (5,5), (5,6), (6,4), (6,5), (6,6) → **6 cases**  
- Total outcomes: \(6 \times 6 = 36\)  
- Probability: **\(6/36 = 1/6\)**  

---

### **2. A bag contains 5 red, 4 blue, and 3 green balls. Two balls are drawn at random. What is the probability that they are of different colors?**  
**Solution:** Total ways to choose any 2 balls:  
\[
\binom{12}{2} = \frac{12!}{2!(10!)} = 66
\]  
Ways to pick 2 same-color balls:  
- Red: \(\binom{5}{2} = 10\)  
- Blue: \(\binom{4}{2} = 6\)  
- Green: \(\binom{3}{2} = 3\)  
Total same-color cases: **\(10 + 6 + 3 = 19\)**  
Different-color cases: **\(66 - 19 = 47\)**  
Probability: **\(47/66\)**  

---

### **3. A committee of 3 is randomly chosen from 5 men and 4 women. What is the probability that the committee has at least one woman?**  
**Solution:**  
Total ways to choose any 3:  
\[
\binom{9}{3} = 84
\]  
Ways to choose all men:  
\[
\binom{5}{3} = 10
\]  
Probability:  
\[
1 - \frac{10}{84} = \frac{74}{84} = \frac{37}{42}
\]  

---

### **4. A fair coin is tossed 4 times. What is the probability of getting exactly 2 heads?**  
**Solution:**  
Ways to get 2 heads:  
\[
\binom{4}{2} = 6
\]  
Total outcomes: \(2^4 = 16\)  
Probability: **\(6/16 = 3/8\)**  

---

### **5. If two people are randomly selected, what is the probability that they share the same birthday (assuming 365 days in a year)?**  
**Solution:**  
First person can have any birthday: **365/365**  
Second person must match: **1/365**  
Total probability: **\(1/365\)**  

---

### **6. A deck of 52 cards is shuffled. What is the probability that the top two cards are both aces?**  
**Solution:**  
Probability of first ace: \(4/52\)  
Probability of second ace: \(3/51\)  
Total probability:  
\[
\frac{4}{52} \times \frac{3}{51} = \frac{1}{221}
\]  

---

## **Permutation & Combination Problems**

### **11. In how many ways can the letters of the word "PROBABILITY" be arranged?**  
**Solution:**  
Total letters: **11**  
Repeated: B (2), I (2)  
\[
\frac{11!}{2!2!} = 19958400
\]  

---

### **12. In how many ways can a team of 4 be formed from 8 people if 2 particular people refuse to be on the same team?**  
**Solution:**  
Total teams: **\(\binom{8}{4} = 70\)**  
Teams where both are together: **\(\binom{6}{2} = 15\)**  
Valid teams: **\(70 - 15 = 55\)**  

---

### **13. How many ways can 3 people be seated in a row such that two particular people are always together?**  
**Solution:**  
Treat the two as a unit → **2 units + 1 person → 3 objects**  
Arrangements: **\(3! = 6\)**  

---

### **14. A class of 10 students is lined up in a row. In how many ways can two particular students be seated next to each other?**  
**Solution:**  
Treat them as a unit → **9 objects**  
Arrangements: **\(9! \times 2! = 725760\)**  

---

### **15. A committee of 5 is to be formed from 7 men and 6 women. How many ways can this be done if at least 3 women must be included?**  
**Solution:**  
(3W, 2M) + (4W, 1M) + (5W, 0M)  
\[
\binom{6}{3} \binom{7}{2} + \binom{6}{4} \binom{7}{1} + \binom{6}{5} \binom{7}{0}
\]  
\[
(20 \times 21) + (15 \times 7) + (6 \times 1) = 420 + 105 + 6 = 531
\]  

---

### **16. How many ways can 3 boys and 3 girls be seated in a row such that no two girls sit together?**  
**Solution:**  
Arrange boys: **\(3!\)**  
Arrange girls in gaps: **\(3!\)**  
Total ways: **\(6 \times 6 = 36\)**  

---

I hope this helps! Let me know if you want any other problems or explanations! 🚀
