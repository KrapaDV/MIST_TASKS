# BANDIT OVERTHEWIRE

# Bandit Level 12 → Level 13
Level Goal
The password for the next level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed. For this level it may be useful to create a directory under /tmp in which you can work. Use mkdir with a hard to guess directory name. Or better, use the command “mktemp -d”. Then copy the datafile using cp, and rename it using mv (read the manpages!)

# Terminal Inputs
  ssh bandit12@bandit.labs.overthewire.org -p 2220
  Cat data.txt
  cd ..
  cd ..
  cd temp
  ls -l
  cat data8

# Password
  FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn