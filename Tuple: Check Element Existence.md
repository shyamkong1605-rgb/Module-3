# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
      tup = eval(input("Enter a tuple of elements with characters and numbers:"))
      if 'n' in tup and 8 in tup :
          print ("The character 'n' and the number (8) are exists in the given tuple")
      elif 'n' in tup and 8 not in tup :
          print ("The character 'n' exists in the given tuple but the number (8) doesn't exist")
      elif 'n' not in tup and 8 in tup :
          print ("The number (8) exists in the given tuple but the character 'n' doesn't exist")
      else:
           print("Both 'n' and 8 are not exist in the givn tuple")

## Output
<img width="1918" height="519" alt="503489947-bee11baa-7909-4950-80b1-ffb930047403" src="https://github.com/user-attachments/assets/b6355c1a-8652-42aa-9749-fc88c77d01f3" />


## Result
Thus, The Python program that checks if the element 'n' and the element 8 exist within a given tuple was executed successfully.
