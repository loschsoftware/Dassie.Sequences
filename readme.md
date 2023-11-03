# Dassie.Generators
A library adding some basic generator types to Dassie.

Usage:
````dassie
import Dassie.Generators

l = rdint "Length: "
n = rdint "Factor: "
		
list = seqtools.unwrap seqtools.mul l, n
println formatArray list
````