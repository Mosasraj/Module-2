## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num=int(input())
temp =num
rev=0
while num>0:
    rem=num%10
    rev=(rev*10)+rem
    num//=10
    
if rev==temp:
    print("The given number {} is a Palindrome".format(temp))
else:
    print("The given number {} is not a palindrome".format(temp))

```
## Output

![image](https://github.com/user-attachments/assets/80f9d627-ce88-4f65-bed0-b5def6640326)

## Result
Thus the given program is verified and executed sucessfully
