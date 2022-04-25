# Internship task - B

Let’s play a game with numbers. You are given sequence of numbers 1...n and a number x = 3.
Every round you will remove from the sequence numbers that fulfils following two conditions:
1. number is divisible by x

2. number contains digit sum of x

To get digit sum of number x you keep summing single digits until you get single digit number. For example: digit_sum(56) => 5+6 = 11 => 1+1 = 2

Initial value of x = 3.
Amount of removed numbers will be your x for next round.
Game ends when you remove 0 numbers (x==0).

```vim
0. 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 	x = 3 
1. 1 2 _ 4 5 _ 7 8 _ 10 11 _ _ 14 _ 16 17 _ 19 20 		x = 7, digit_sum = 7
2. 1 2 _ 4 5 _ _ 8 _ 10 11 _ _ _ _ 16 _ _ 19 20 		x = 3, digit_sum = 3 
3. 1 2 _ 4 5 _ 7 8 _ 10 11 _ _ _ _ 16 _ _ 19 20 		x = 0
```

The game ended after 3 rounds.
Write a program that works for any n. Test it for n = 9999999.
After how many round this game will end?

Finish the program:

https://www.online-python.com/8TGyERdwps

```python
def play(n, x):
    print("3")

if __name__ == "__main__":
    play(n=20, x=3)
```
