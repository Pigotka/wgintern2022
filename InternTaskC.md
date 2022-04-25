
# Internship task – C

Our marketing wants to create a logo for our top-secret project. They decided to base the logo on the three most common characters in the project name. They are now trying out various combinations and asked our developer for help.

Given a string, which is the project name in lowercase letters, your task is to find the top three most common characters in the string.

* Print the three most common characters along with their occurrence count.

* Sort in descending order of occurrence count.

* If the occurrence count is the same, sort the characters in alphabetical order.

For example, according to the conditions described above, **Wargaming** would have the logo made from letters A, G, I.

**Input Format**

A single string name.

**Constraints**

* len(name) < 107

* has at least 3 distinct characters

**Output Format**

Print the three most common characters along with their occurrence count each on a separate line.  
Sort output in descending order of occurrence count.  
If the occurrence count is the same, sort the characters in alphabetical order.

**Sample Input**
```
ahhcccdde
```

**Sample Output**

```
c 3
d 2
h 2
```

**Explanation**

Here, c occurs 3 times. It is printed first.  
Both d and h occur 2 times. So, d is printed in the second line and h in the third line because d comes before h in the alphabet.

**Finish the program:**

https://www.online-python.com/zwHZgC3v5V

```python
def countIt(name):
    print("c 3")
    print("d 2")
    print("h 2")

if __name__ == "__main__":
    countIt(name="ahhcccdde")
```
