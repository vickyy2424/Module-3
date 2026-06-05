# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

```
L=[153,147,124,102] 
 
print(sum(L)))
```

## Output

<img width="542" height="205" alt="image" src="https://github.com/user-attachments/assets/c1992e82-cf06-4064-b8d1-2f5458dd94b5" />

## Result

Thus, the program has been successfully executed.
# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program

```
import re
l1=[] 

items=['goal', 'new', 'user', 'sit', 'eat', 'dinner'] 
for i in items: 

   if not re.search(r"e",i): 
      l1.append(i) 

print(l1)
```
## Output

<img width="405" height="139" alt="image" src="https://github.com/user-attachments/assets/5e9953c8-c2f5-454b-9bb9-88d7bb548f51" />

## Result

Thus, the program has been successfully executed.
# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program

```
def remove(a,n):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
a=input()
n=int(input())
remove(a,n)
```

## Output

<img width="685" height="142" alt="image" src="https://github.com/user-attachments/assets/028b13f0-7e77-489b-891c-781a70ee45a7" />

## Result

Thus the program has been successfully executed
# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

```python
string="google" 

if string==string[::-1]: 

   print ("The entered string is palindrome")

else: 

   print ("The entered string is not palindrome")
```

## Output

<img width="529" height="119" alt="image" src="https://github.com/user-attachments/assets/6dc216e9-e0ec-40f2-b6b7-55247e59ab4a" />

## Result

Thus the program has been successfully executed
# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program

```python
a=eval(input())
print("n" not in a)
print("8" in a)
```

## Output

<img width="740" height="190" alt="image" src="https://github.com/user-attachments/assets/1eada1ee-053f-4216-a425-1b9d6fb64d8c" />

## Result

Thus the given program is verified and executed sucessfully
