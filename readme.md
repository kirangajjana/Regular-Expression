# Regular Expression

   - Regular Expression is a special sequence of characters that uses a search patterns to find a string or set of strings.
   ---
   **Functions of Regular Expression**
   >match()

   >search()

   >findall()

   >split()

   >sub()

   **1.Match Function**

   The match function in Python is part of the re module. It is used to search for a pattern in a string and return a match object if the pattern is found. The syntax of the match function is as follows

```python
import re
a="haii everyone todays date is march 20"
match=re.match("haii",a)
print(match)
```
- Inside the match function we have to pass string that we want to find and the variable of the text where we want to find the string.

- By using match function we can find wether the string is available in the starting or not.


**2.Search Function**

- The search function takes a regular expression pattern and a string and searches for that pattern within the string. If the search is successful, search() returns a match object or None otherwise