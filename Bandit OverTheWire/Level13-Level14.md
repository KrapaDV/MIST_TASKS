# BANDIT OVERTHEWIRE

# Bandit Level 13 → Level 14
Level Goal
The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. Note: localhost is a hostname that refers to the machine you are working on

# Terminal Inputs
  ls
  ssh -i sshkey.private bandit14@localhost -p 2220
  cd /etc
  cd bandit_pass
  cat bandit14

# Password
  MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS