##### ***1.input-and-output-functions***

#####  ***1.1 input function commonly we take input from the user and give a output***
```
name = input("enter your age: ") #every input we given in the program that program considerd as string
age = int(input("enter your age: ")) #convert string into intiger
```

####  **1.2 Output to the Console**:
#### **we use print() function use to disply the out put**
```
print("Hello, " + name + "! You are " + str(age) + " years old.")
print(f"Hello, {name}! You are {age} years old.")
```

#2.String Manipulation
#types of string manipulation
 **2.1 Common String Operations**:
  ``` python
  first_fruit = "mango"
  second_fruit = "apple"
  total_fruits = first_fruit + " " + second_fruit
  print(total_fruits) # "mango apple"
  ```
  **2.2 Repetition**: Repeating a string multiple times using the * operator.
    ```python
    name = "sudeep" *3
    print(name) #out put : "sudeep sudeep sudeep"
    ```
    
#### **2,3string methodes**
- ~ upper() - to converts to uppercase
- ~ lower() - to convet to lowercase
- ~ strip() - to strip the all spaces
- ~ replace(old,new) - to replace old to nwe

```python
message = "   hello, world!   "
print(message.upper()) #output : "HELLO, WORLD!"
print(message.lower()) #output : "hello, world!"
print(message.strip("_", " ")) #output : "hello,world!"
print(message.replace("world","python") #output : "hello, python"
```

#### **3. Accessing String Characters:**
```python
student = " chetan "
print(student[0]) #output: "c"
print(student[3]) #output: "t"
```
You can also use **negative indexing** to start counting from the end of the string.
```python
print(text[-1])  # Output: n
print(text[-3])  # Output: h
```

#### ** Slicing Strings:**
You can extract a portion (substring) of a string using slicing.

```python
text = "Python Programming"
print(text[0:6])  # Output: Python (extracts from index 0 to 5)
print(text[:6])  # Output: Python (same as above)
print(text[7:])  # Output: Programming (from index 7 to the end)
```

---

### **3. Comments in Python**

Comments are ignored by the Python interpreter and are used to explain the code or leave notes for yourself or others. They do not affect the execution of the program.

- **Single-line comments** start with `#`:
  ```python
  # This is a single-line comment
  print("Hello, World!")
  ```

- **Multi-line comments** can be written using triple quotes (`"""` or `'''`). These are often used to write detailed explanations or temporarily block sections of code:
  ```python
  """
  This is a multi-line comment.
  It can span multiple lines.
  """
  print("Hello, Python!")
  ```

---

### **4. Escape Sequences**
Escape sequences are special characters in strings that start with a backslash (`\`). They are used to represent certain special characters.

Some commonly used escape sequences:
- `\n`: New line
- `\t`: Tab space
- `\\`: Backslash

#### **Example:**
```python
print("Hello\nWorld")  # Output: 
# Hello
# World

print("Hello\tPython")  # Output: Hello    Python
```

---

### **Homework**

1. **Simple Greeting Program**:
   Write a Python program that asks the user for their name and age, then prints a personalized greeting message. Use both the `+` operator and f-strings for output.

   **Example**:
   ```python
   Enter your name: Alice
   Enter your age: 25
   Output: Hello, Alice! You are 25 years old.
   ```

2. **String Manipulation Exercise**:
   Write a Python program that:
   - Takes a sentence as input from the user.
   - Prints the sentence in all uppercase and lowercase.
   - Replaces all spaces with underscores.
   - Removes leading and trailing whitespace.

   **Example**:
   ```python
   Input: "   Python is awesome!   "
   Output:
   Uppercase: "PYTHON IS AWESOME!"
   Lowercase: "python is awesome!"
   Replaced: "___Python_is_awesome!___"
   Stripped: "Python is awesome!"
   ```

3. **Character Counter**:
   Write a Python program that:
   - Asks the user for a string.
   - Prints how many characters are in the string, excluding spaces.

   **Example**:
   ```python
   Input: "Hello World"
   Output: "Number of characters (excluding spaces): 10"
   ```

4. **Escape Sequence Practice**:
   Write a Python program that uses escape sequences to print the following output:

   **Example**:
   ```
   Hello
       World
   This is a backslash: \
   ```

---

 
    

    
  
  
