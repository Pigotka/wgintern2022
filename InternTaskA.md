
# Internship task - A

Recently we organized running competition for our developers. Everyone saw that James won. But nobody noticed who finished the run on second place. Fortunately, we have logs with names and positions. The problem is that there were thousands of runners and we need you to write a program that can find a runner-up for us.

**Input Format**

A single file having name and place on each line. Name is separated from place with semicolon. Be careful list can be very long.

**Output Format**

Name of runner-up

**Sample Input**

```vim
Peter Hass;3

Julia Tiny;4

Tomas Novak;2

Tina Bell;5

James Hall;1
```

**Sample Output**
```vim
Tomas Novak
```

**Explanation**

According to input file Tomas finished the run on second place therefore we print Tomas to the output.

**Finish the program:**

https://www.online-python.com/tR485F3HhA

```python
def findRunnerUp(file):
    print("Tomas Novak")

if __name__ == "__main__":
    f = open('input.txt')
    findRunnerUp(f)
```
