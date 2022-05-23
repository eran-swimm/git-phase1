# Initialize the repo

We create an empty folder, and initialize an empty repo
You can create a repo from an existing folder, or clone other person repo
but later on this
```
mkdir git-lab
cd git-lab
git init # this will initialize an empty repo
```

# Add some files

We are going to create new python files. The first file will implement function 
to return the longest string between two

create empty file `functions.py` and paste the below code there

```python
def get_longest(s1, s2):
    if len(s1) > len(s2):
      return s1
    return s2
```
