# 19CS301-Module8
### Register No - 212222020029
### Name - Subashree A

# ExNo: 8.1 HackerRankChallenges
### Aim: To Write a python program to find the amount paid by Vimla, If 5% discount was given and 2% CST was paid.Vimla purchased a microwave oven with the price Rs. 25,000. Finalamount = amount +cst_amount - discount_amountmax_speed(),change_gear() override the same methods of base class  using method overriding
### Algorithm:

**STEP 1:** Start.

**STEP 2:** Initialize variable `amt` with 25000.

**STEP 3:** Calculate `final` as:  
&nbsp;&nbsp;&nbsp;&nbsp;`amt + (2% of 25000) - (5% of 25000)`.

**STEP 4:** Print the value of `final`.

**STEP 5:** Stop.

### Program:
```
amt = 25000
final=amt+((2/100)*25000)-((5/100)*25000)
print(final)

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/c57524d3-e975-47e3-9504-00414d48028e)

### Result: Thus, the given program is implemented and executed successfully .

# ExNo: 8.2 HackerRankChallenges
### Aim: To Write a python program to display elements from a list, present at odd index positions
### Algorithm:

**STEP 1:** Start.

**STEP 2:** Take input `a` (number of elements).

**STEP 3:** For each `i` in range 0 to `a-1`:  
- Take input `b`.  
- If `i` is odd (`i % 2 != 0`), print `b` with a space.

**STEP 4:** Stop.

### Program:
```
a = int(input())
for i in range (0,a):
    b = int(input())
    if i%2!=0:
        print(b,end=" ")

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/71488b37-fe18-44bd-af2e-5cc09941f377)

### Result: Thus, the given program is implemented and executed successfully .

# ExNo: 8.3 HackerRankChallenges
### Aim: To write a python program to find the runner up score Given the participants' score sheet for your University Sports Day. You are given  scores. Store them in a list and find the score of the runner-up.
### Algorithm:

**STEP 1:** Start.

**STEP 2:** Take input `n` (number of elements).

**STEP 3:** Take input list `a` of `n` integers.

**STEP 4:** Convert list `a` to a set to get unique elements.

**STEP 5:** Sort the unique elements in descending order and store in `uniq`.

**STEP 6:** If the length of `uniq` is greater than 1, print the second element (`uniq[1]`).

**STEP 7:** Otherwise, print `"no"`.

**STEP 8:** Stop.

### Program:
```
n = int(input())
a = [int(x) for x in input().split()]
uniq = sorted(set(a), reverse = True)
if len(uniq)>1:
    print(uniq[1])
else:
    print("no")

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/6185a556-40d5-4722-a56d-6736670e42db)

### Result: Thus, the given program is implemented and executed successfully .

# ExNo: 8.4 HackerRankChallenges
### Aim: To Develop a python program to square all the even numbers and cube all odd numbers from a list of integers. Get the starting and ending range to create a list
### Algorithm:

**STEP 1:** Start.

**STEP 2:** Define a function `fun(f, l)` that:
- Returns a list of integers from `f` to `l` inclusive.

**STEP 3:** Define a function `cube(num)` that:
- If `num` is even, returns the square of `num`.
- Otherwise, returns the cube of `num`.

**STEP 4:** Take integer inputs `f` and `l` from the user.

**STEP 5:** (Optional) Call `fun(f, l)` to get the list of numbers.

**STEP 6:** (Optional) For each number in the list, call `cube(num)` to get the respective value.

**STEP 7:** Stop.

### Program:
```
def fun(f,l):
    return list(range(f,l+1))
def cube(num):
   
        if num%2==0:
             cube=num*num
        else:
             cube=num**3
        return cube
f = int(input())
l = int(input())

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/f037bf5f-5cd8-48b9-926c-243f5436fe59)

### Result: Thus, the given program is implemented and executed successfully .

# Ex No: 8.5 SEB-Vowels
# README

### Aim:
To write a Python program to check and accept the given string if it contains all vowels i.e. ‘a’, ‘e’, ‘i’, ‘o’, ‘u’ using recursion.

### Algorithm:

**STEP 1:** Start.  
**STEP 2:** Take input string `str`.  
**STEP 3:** Check if all vowels `'a'`, `'e'`, `'i'`, `'o'`, `'u'` are present in the string using `if` condition.  
**STEP 4:** If present, print "Accepted", else print "Not Accepted".  
**STEP 5:** Stop.

### Program:
```python
str = input()
if "a" in str and "e" in str and "i" in str and "o" in str and "u" in str:
    print("Accepted")
else:
    print("Not Accepted")
```
### Output:
![image](https://github.com/user-attachments/assets/efeaaf4b-4074-46d0-a414-85c6543837bd)
# Result: Thus the program was executed successfully.




