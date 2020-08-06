# Ex 9.2-2: #

(a) ```findVal```: the mutant is always reached, even if x = null.

(b) ```findVal```: infection always occurs, even if x = null.

(c) Will always return the correct output. Accept for ```numbers[0]```.

(d) All input with ```val``` in the ```numbers[0]``` strongly kill the mutants.

# Ex 9.2-3: #

(a) ```sum```: never reach the mutant if x = null or x is empty.

(b) ```sum```: any input with all zeroes will reach but infection won't occur.

(c) ```sum```: any nonzero entry work.

(d) All input with ```sum != 0``` strongly kill the mutants.