## BANDIT OVERTHEWIRE

# Bandit Level 6 → Level 7
Level Goal
The password for the next level is stored somewhere on the server and has all of the following properties:

owned by user bandit7
owned by group bandit6
33 bytes in size

# Terminal Inputs
  cd ..
  cd ..
  ls
  find . -type f -size 33c -user bandit7 -group bandit6 2>/dev/null
    ./var/lib/dpkg/info/bandit7.password
  cat ./var/lib/dpkg/info/bandit7.password
  
# Password
  morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj