# Modular Arithmetic

In **modular arithmetic**, we have numbers that repeat after a selected modulus given by an integer n.

The numbers are represented by the set {0, 1, .., n-1} after which they cycle back to the beginning. 

We represent a number as p (mod n), for some integer p.

In fact, we use this system every day when we talk about numbers on a clock.

| ![clock](https://user-images.githubusercontent.com/51001263/73673018-dd9fb180-46a5-11ea-9c9f-ea8b3afa3ecb.gif)| 
|:--:| 
| *Numbers on a clock are mod 12.* |

The numbers go from 1 to 12, but when you go to 13 - it becomes 1 o'clock again.

How can we compute something like 153 (mod 12)? 

The answer is quite simple, we divide the number by 12 and the answer is given by the remainder. 

153 = 12*12 + 9

The remainder is 9, so 153 (mod 12) ≡ 9 (mod 12).
