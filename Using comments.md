Single Line Comment

We can comment out a whole line:
```
# This is a full like comment
```
or we can comment at the end of a line:
```
2 + 2 # This will add the numbers
```
What About Block Comments?

Python does not have the concept of block commenting that you may have encountered in other langauges. Many people mistake a triple quoted string as being a comment, but it is not, it's a multi-line string. That being said, multi-line strings can functionally work like comments, but they will still be allocated into memory.
```
"""
This is not a block comment,
but it will still work when you really need
for some lines of code to not execute.
"""
```
