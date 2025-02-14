# Tricky Probability and Combination Problems with Solutions

## Basic Level

### Problem 1: Birthday Problem
**Question:**  
At a party, what's the probability that among 23 people, at least 2 share the same birthday? (Assuming 365 days in a year, no leap years)

**Solution:**
1. It's easier to calculate the probability of no shared birthdays first
2. P(no shared birthdays) = (365/365) × (364/365) × (363/365) × ... × (343/365)
3. = 365!/(365-23)! × (1/365^23)
4. ≈ 0.492703...
5. Therefore, P(at least one shared birthday) = 1 - 0.492703 ≈ 0.507
6. This means there's about a 50.7% chance of at least two people sharing a birthday

### Problem 2: Card Drawing
**Question:**  
From a deck of 52 cards, you draw 3 cards. What's the probability of getting 3 cards of the same suit in ascending order?

**Solution:**
1. Let's break this into parts:
   * First, we need to select a suit (4 choices)
   * Then we need to select 3 cards from that suit in ascending order
2. For one suit:
   * Total ways to select 3 cards from 13 cards = 13C3
   * These must be in ascending order (only 1 way to arrange them in ascending order)
3. Total favorable outcomes = 4 × 13C3 × 1 = 4 × 286 = 1,144
4. Total possible outcomes = 52C3 = 22,100
5. Therefore, probability = 52/5,525

### Problem 3: Ball Selection
**Question:**  
A box contains 6 red balls and 4 blue balls. Two balls are drawn without replacement. Given that at least one ball is red, what's the probability that both balls are red?

**Solution:**
1. This is a conditional probability problem
2. Let's use Bayes' Theorem:
   * P(both red | at least one red) = P(both red) / P(at least one red)
3. P(both red) = 6C2/10C2 = 15/45
4. P(at least one red) = 1 - P(no red) = 1 - 4C2/10C2 = 1 - 6/45 = 35/45
5. Therefore, P(both red | at least one red) = (15/45)/(35/45) = 15/35

## Intermediate Level

### Problem 4: Word Arrangement
**Question:**  
How many different ways can you rearrange the letters in "MISSISSIPPI"?

**Solution:**
1. Total letters = 11 (4 'S', 4 'I', 2 'P', 1 'M')
2. This is a permutation with repetition
3. Formula = n!/(n1!×n2!×...×nk!) where n is total letters and ni is repetition of each letter
4. = 11!/(4!×4!×2!×1!)
5. = 11!/(4!×4!×2!)
6. = 34,650

### Problem 5: Circular Arrangement
**Question:**  
In how many ways can 8 people be seated around a circular table if rotations of the same arrangement are considered identical?

**Solution:**
1. For circular arrangements:
   * Fix one person's position (reduces problem to linear arrangement of n-1 people)
   * Remaining people can be arranged in (n-1)! ways
2. Here, n = 8
3. Therefore, number of arrangements = 7!
4. = 7 × 6 × 5 × 4 × 3 × 2 × 1
5. = 5,040


### Problem 6: Committee Formation
**Question:**  
From a group of 5 men and 4 women, in how many ways can a committee of 3 men and 2 women be formed where one woman must be the chairperson?

**Solution:**
1. Break this into steps:
   * Select 3 men from 5 men: 5C3
   * Select 2 women from 4 women: 4C2
   * Choose 1 woman from the 2 selected women to be chairperson: 2C1
2. Apply multiplication principle:
   * Total ways = 5C3 × 4C2 × 2C1
   * = 10 × 6 × 2
   * = 60

## Advanced Level

### Problem 7: Dice Probability
**Question:**  
Three different dice are rolled. What's the probability of getting numbers in strictly increasing order?

**Solution:**
1. First, count favorable outcomes:
   * Numbers must be different and increasing
   * First die can be 1-4
   * Second die must be larger than first but less than third
   * Third die must be larger than second
2. Count total arrangements:
   * For first number (n1): 4 possibilities
   * For second number (n2): 5-n1 possibilities
   * For third number (n3): 6-n2 possibilities
3. Total favorable outcomes = 20
4. Total possible outcomes = 6 × 6 × 6 = 216
5. Therefore, probability = 20/216

[Previous problems and solutions remain the same through Problem 7...]

### Problem 8: Number Formation
**Question:**  
How many different 6-digit numbers can be formed using digits 1 to 9 if no digit can be repeated and the number must be divisible by 4?

**Solution:**
1. For a number to be divisible by 4, its last two digits must form a number divisible by 4
2. From digits 1-9, possible two-digit combinations divisible by 4 are:
   * Last digit must be even (2,4,6,8)
   * Second-last digit can be any remaining digit
3. Count systematically:
   * Choose last digit: 4 choices (2,4,6,8)
   * Choose second-last digit: 8 choices (remaining digits except last)
   * Choose remaining 4 digits: 7P4 (permutation of remaining 7 digits)
4. Total = 4 × 8 × 7P4 = 4 × 8 × 840 = 15,120

### Problem 9: Stair Climbing
**Question:**  
In how many ways can you climb n stairs if you can take either 1 or 2 steps at a time?
For n=5

**Solution:**
1. This follows the Fibonacci sequence pattern
2. For n=5, let's solve step by step:
   * Let's list all possibilities:
     - 1,1,1,1,1
     - 1,1,1,2
     - 1,1,2,1
     - 1,2,1,1
     - 2,1,1,1
     - 1,2,2
     - 2,1,2
     - 2,2,1
3. Total ways = 8
4. General formula: F(n) = F(n-1) + F(n-2)
   where F(1) = 1 and F(2) = 2

### Problem 10: Exam Questions
**Question:**  
A student must answer 8 out of 12 questions in an exam, but questions 1 and 2 are compulsory. How many different combinations of questions can they choose?

**Solution:**
1. Given:
   * Total questions = 12
   * Must answer = 8
   * Questions 1 and 2 are compulsory
2. Strategy:
   * Questions 1 and 2 are already selected
   * Need to select 6 more questions from remaining 10 questions
3. This becomes: 10C6
4. Calculate: 10!/(6!(10-6)!)
   = 10!/(6!4!)
   = 210

### Problem 11: Permutation with Fixed Points
**Question:**  
What's the probability that a randomly selected permutation of (1,2,3,4,5) has exactly two fixed points?

**Solution:**
1. Understanding fixed points:
   * A fixed point occurs when a number remains in its original position
   * We need exactly two numbers to stay in place
2. Solution steps:
   * First, choose which 2 numbers stay fixed: 5C2
   * Then arrange remaining 3 numbers with no fixed points (derangement)
   * Derangement of 3 numbers = 2
3. Calculate:
   * Total favorable outcomes = 5C2 × 2 = 20
   * Total permutations = 5! = 120
   * Probability = 20/120 = 1/6

### Problem 12: Conditional Card Probability
**Question:**  
From a standard deck, what's the probability of drawing a flush in a 5-card hand, given that you have at least one ace?

**Solution:**
1. Use conditional probability:
   P(flush|ace) = P(flush and ace)/P(at least one ace)
2. Calculate components:
   * Ways to get flush with ace = 4C1 × 12C4 (choose suit, then other cards)
   * Ways to get flush without ace = 4C1 × 12C5
   * Total hands with ace = 52C5 - 48C5
3. Therefore:
   * P(flush and ace) = 4C1 × 12C4
   * P(at least one ace) = 52C5 - 48C5
   * Final answer = (4C1 × 12C4 - 11C4)/(52C5 - 48C5)

### Problem 13: Word Arrangement with Constraints
**Question:**  
How many different ways can you arrange the letters in "ENVIRONMENT" such that no two vowels are adjacent?

**Solution:**
1. Identify components:
   * Vowels: E, I, O, E (4 letters)
   * Consonants: N, V, R, N, M, N, T (7 letters)
2. Strategy:
   * First arrange consonants with gaps: _ N _ V _ R _ N _ M _ N _ T _
   * Then place vowels in gaps
3. Calculate:
   * Arrange 7 consonants (with repetition): 7!/(3!)
   * Choose 4 positions from 8 gaps for vowels: 8C4
   * Arrange 4 vowels (with repetition): 4!/(2!)
4. Total = (7!/(3!)) × 8C4 × (4!/(2!)) = 75,600

### Problem 14: Line Arrangement with Constraints
**Question:**  
In how many ways can 4 boys and 4 girls be arranged in a line such that no two boys are adjacent?

**Solution:**
1. Key insight:
   * Girls must create gaps between boys
   * We need 5 positions for girls (including ends)
2. Solution method:
   * First arrange 4 girls in 5 possible positions: 5!
   * Then arrange 4 boys in remaining positions: 4!
3. Calculate:
   * Total arrangements = 5! × 4! = 2,880

### Problem 15: Conditional Coin Probability
**Question:**  
What's the probability of getting exactly three heads when five coins are tossed, given that at least two heads appeared?

**Solution:**
1. Use conditional probability:
   P(3H|≥2H) = P(3H)/P(≥2H)
2. Calculate:
   * P(3H) = 5C3 × (1/2)⁵ = 10/32
   * P(≥2H) = 1 - P(1H) - P(0H)
   * = 1 - 5C1(1/2)⁵ - (1/2)⁵
   * = 26/32
3. Therefore:
   * P(3H|≥2H) = (10/32)/(26/32) = 10/26

