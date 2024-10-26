# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
# Step 1:
Open the text file in read mode.
# Step 2:
Read the content of the file.
# Step 3: 
Split the content into words based on whitespace.
# Step 4:
Count the number of words in the list created.
# Step 5:
Print the total word count.
# Step 6:
Close the file.
## PROGRAM:
```
# Developed By : HARSHITHA V
# Register No : 212223230074
```
```
def count_words_in_file(filename):
    try:
        with open(filename, 'r') as file:
            content = file.read()
            words = content.split()
            return len(words)
    except FileNotFoundError:
        print(f"The file {filename} does not exist.")
        return 0

filename = 'example.txt'  # Use the name of your uploaded file
total_words = count_words_in_file(filename)
print(f"Total word count: {total_words}")

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/e59a7718-1900-4211-a209-e85e644923a2)



## RESULT:
Thus the program is written to find the word count from a text.
