---
title: Build a menu with for loop
tags: utility
expertise: intermediate
firstSeen: 2022-08-24T12:48:00-04:00
---

This snippet helps you build a menu and a conditional statement as a response.

- Build a menu using a simple for loop as an interactive input/output.
- Build a conditional statement that shows the output you selected in the menu.
- Change the input and the output according to your needs.

```py
print("\n|::THIS IS A MENU BAR::|\n")
options = {1:'1. Option 1.', 2:'2. Option 2.', 3:'3. Option 3.',4:'4. Option 4.',5:'5. Option 5.'}
for value in options:
    print(options[value])
options = int(input("\nSelect an option: "))
```

```py
if menu == 1:
    print("\nYou selected option 1.")
elif menu == 2:
    print("\nYou selected option 2.")
elif menu == 3:
    print("\nYou selected option 3.")
elif menu == 4:
    print("\nYou selected option 4.")
elif menu == 5:
    print("\nYou selected option 5.")
else:
    print("\nYou haven't selected an option.")
```
