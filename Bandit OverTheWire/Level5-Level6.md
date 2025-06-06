## BANDIT OVERTHEWIRE

# Bandit Level 5 → Level 6
Level Goal
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

human-readable
1033 bytes in size
not executable

# Terminal Inputs
  Cd inhere
    Maybehere00
  find . -type f -size 1033c ! -executable -exec file {} + | grep ASCII
    Maybehere00
  find . -type f -size 1033c ! -executable -exec file {} + | grep ASCII
    ./.file2: ASCII text, with very long lines (1000)
Cd maybehere 07
Cat <.file2

# Password
  HWasnPhtq9AVKe0dmk45nxy20cvUa6EG