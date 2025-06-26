# Group 3 Big Data

## Student Names and IDs

- Manzi Arsene ID: 27435
- Nshuti Cesar ID: 25421 
- Humure Enock ID: 27394
- Ndagijimana Cedric ID: 27655
- Cyusa Niyibaho Landry ID: 25539 
- Nziza Prince ID: 26651

---

## Question 1: Age Calculator

**Description:**  
This program asks the user for their name and year of birth, then calculates and displays their age based on the current year (2025).

```python
def calculate_age(name, year_of_birth):
    current_year = 2025
    age = current_year - year_of_birth
    print("Thank you")
    print(f"{name}, your age is: {age}")

user_input1 = input("Enter your name: ")
name = str(user_input1)

user_input2 = input("Enter your year of birth: ")
yearOfBirth = int(user_input2)

calculate_age(name, yearOfBirth)
```
## Question 2: Palindrome Checker

**Description:**  
This program checks if a given word is a palindrome (a word that reads the same forward and backward).

```python
def check_palindrome(word):
    i = 0
    j = len(word) - 1 
    is_palindrome = True  

    while i < j:
        if word[i] != word[j]:  
            is_palindrome = False
        i += 1
        j -= 1

        if is_palindrome:
            print("Yes, it is a palindrome") 
            break
        else:
            print("No, it is not a palindrome")
            break

user_input = input("Enter a word: ")
word = str(user_input)
check_palindrome(word)
```
## Question 3:  Combine Text and Print characters

**Description:**  
This program combines two pieces of text entered by the user, then prints each character of the combined string one by one.

```python
def combine_text(text1, text2):
    full_text = text1 + text2
    i = 0
    j = len(full_text)

    while i < j:
        print(f"{full_text[i]}")
        i += 1  

    print("Thank you for using my application")

user_input1 = input("Enter first text: ")
text1 = str(user_input1)

user_input2 = input("Enter second text: ")
text2 = str(user_input2)

combine_text(text1, text2)
```
