# Bandit Level 5 → Level 6

### Challenge

Find the password stored in a file under the `inhere` directory that is human-readable, 1033 bytes in size, and not executable.

### Commands Used

```bash
cd inhere
find . -type f -size 1033c ! -executable
cat ./maybehere07/.file2
```

### Solution

Password found using `find` to filter by file type (`-type f`), exact size of 1033 bytes (`-size 1033c`), and non-executable permissions (`! -executable`).

### Password

pXa26xhMWaC2SvDotA4r9EgZkulOeSBW
