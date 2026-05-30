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
```

def palindrome(a):
    x1=a[::-1]
    if a==x1:
       print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
    
    
        
        
string =input()
palindrome(string)

```

## Output
<img width="948" height="157" alt="438591429-a2db7a2a-9ea9-46ff-a33d-3f3cac2b09eb" src="https://github.com/user-attachments/assets/4232123b-2379-4d9a-8408-3bc31af89554" />


## Result
Thus the program executed successfully.
