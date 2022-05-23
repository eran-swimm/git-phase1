# Initialize the repo

We create an empty folder, and initialize an empty repo
You can create a repo from an existing folder, or clone other person repo
but later on this
```
mkdir git-lab
cd git-lab
git init # this will initialize an empty repo
```

# Create two text files

We are going to two new text files. One file will contains names of countries and one file names of monthes.

* Create an empty file `countries.txt` and paste the following content into it

```
Israel
England
United Kingdom
```

* Create an empty file `months.txt` and paste the following content into it (with the typos)

```
January
Feburary
March
May
April
June
July
Aogust
Saptember
October
November
December
```

# Add and commit
Now we want to add the files to the repo. For this, we are going to run `git add` and then `git commit`

```shell
git add countries.txt months.txt
git commit -m 'initial files'
```

