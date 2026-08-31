##Bandit Level 1 → Level 2

#challenge
Find the password hidden in a file named - located in the home directory.

#cmd used

cat ./-

#solution
Linux commands interpret a bare - as standard input (stdin) or an option flag. Prefixing the filename with the relative path ./ forces cat to read the literal file.


#password
PK8fYLZg2hnHSz83plBL1iEPKdD3QToB
