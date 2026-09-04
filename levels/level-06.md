# Bandit Level 6 → Level 7

### Challenge

Find the password stored somewhere on the server that is owned by user `bandit7`, owned by group `bandit6`, and 33 bytes in size.

### Commands Used

```bash
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password
```

### Solution

Password found using `find /` with properties `-user bandit7`, `-group bandit6`, and `-size 33c`. Redirecting errors with `2>/dev/null` suppresses permission warnings to cleanly output `/var/lib/dpkg/info/bandit7.password`.

### Password

Bmnnvf82KzQlfxgAI2d1zYbr1u9pr3E3
