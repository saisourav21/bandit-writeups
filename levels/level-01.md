<<<<<<< HEAD

# Bandit Level 1 → Level 2

### Challenge

Find the password hidden in a file named `-` located in the home directory.

=======
# Bandit Level 1 → Level 2

### Challenge

Find the password hidden in a file named `-` located in the home directory.

>>>>>>> 11d62b8 (lvl2 -> lvl3)
### Commands Used

```bash
cat ./-
```

### Solution

<<<<<<< HEAD
Password found using `cat ./-` because Linux commands interpret a bare `-` as standard input (stdin) or an option flag. Prefixing the path with `./` forces `cat` to read the literal file.
=======
Password found using `cat ./-` because Linux commands interpret a bare `-` as standard input 'stdin' or an option flag. Prefixing the path with `./` forces `cat` to read the literal file.
>>>>>>> 11d62b8 (lvl2 -> lvl3)

### Password

PK8fYLZg2hnHSz83plBL1iEPKdD3QToB
