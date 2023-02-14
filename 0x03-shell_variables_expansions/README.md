0 - alias ls='rm *': Creates an alias.
1 - echo hello $USER: Prints hello user, where user is the current Linux user.
2 - export PATH=$PATH:/action: Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
3 - echo $PATH | tr -s ':' '\n' | wc -l: Counts the number of directories in the PATH.
4 – printenv: Lists environment variables.
5 - set:  Lists all local variables and environment variables, and functions.
6 - BEST="School": Creates a new local variable.
7 - export BEST="School":  Creates a new global variable.
8 - echo $((128+TRUEKNOWLEDGE)): Prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE
9 - echo $((POWER/DIVIDE)): Prints the result of POWER divided by DIVIDE 
10 - echo $((BREATH**LOVE)): Displays the result of BREATH to the power LOVE
11 - echo $((2#$BINARY)): Converts a number from base 2 to base 10.
12 - echo {a..z}{a..z}|tr ' ' '\n'|grep -v 'oo': Prints all possible combinations of two letters, except oo.
13 - printf "%.2f\n" $NUM: Prints a number with two decimal places, followed by a new line.
100 - printf '%x\n' $DECIMAL: Converts a number from base 10 to base 16.
