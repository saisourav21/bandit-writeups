#Bandit level 13 -> level 14

##Challenge
Connect bandit.labs.overthewire.org via SSH, find password for the net level.

##Commands used
ssh bandit13@bandit.labs.overthewire.org -p 2220
ls
cat sshkey.private
mkdir ssh.key
ls -la ssh.key
chmod 400 ssh.key
ssh bandit14@bandit.labs.overthewire.org -p 2220 -i ssh.key


##solution

The `sshkey.private` file contained the SSH private key required to log in as the next Bandit user. Since SSH refuses to use private keys with insecure permissions, I created a separate directory to store the key and set its permissions to `400` using `chmod`. I then connected to the next level with:

[bash]
`ssh bandit14@bandit.labs.overthewire.org -p 2220 -i ssh.key/sshkey.private`


##Password
aaWecNkG4FhxJQxz07uiwzVP6bJiYS65

