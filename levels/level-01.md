
# Bandit Level 1 → Level 2

### Challenge

Find the password hidden in a file named `-` located in the home directory.

### Commands Used

```bash
cat ./-
```

### Solution

Password found using `cat ./-` because Linux commands interpret a bare `-` as standard input (stdin) or an option flag. Prefixing the path with `./` forces `cat` to read the literal file.

### Password

PK8fYLZg2hnHSz83plBL1iEPKdD3QToB
