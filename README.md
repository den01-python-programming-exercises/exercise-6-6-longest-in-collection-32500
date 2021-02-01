[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=4012423&assignment_repo_type=AssignmentRepo)
# Exercise 6.6 Longest in Collection

The exercise template comes with the class `SimpleCollection` that's familiar from previous exercises. Implement the method `def longest()` for the class, which returns the longest string of the collection. If the collection is empty, the method should return a `None` reference.

```python
j = SimpleCollection("characters")
print("Longest: " + str(j.longest()))

j.add("magneto")
j.add("mystique")
j.add("phoenix")

print("Longest: " + str(j.longest()))
```

```plaintext
Longest: None
Longest: mystique
```
