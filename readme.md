# Dassie.Sequences
A library adding tools for generating and working with number sequences.

Usage:
````dassie
import Dassie.Sequences

l = rdint "Length: "
n = rdint "Factor: "
		
list = seqtools.unwrap seqtools.mul l, n
println formatArray list
````