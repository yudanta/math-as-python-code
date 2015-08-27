#Math As Python Code

###Overview
> Math as python code. 

Is a sample codes for a reference to ease developers transform mathematical notation into python codes. The aim of this sample of codes is to help academic or students to ease transform their mathematical formula or a formula from any paper into python codes by giving them an examples. 

This idea originaly from math as code by Jam3 on github <https://github.com/Jam3/math-as-code>.

###Foreword
This work are covering an examples for list of mathematical symbols into python codes, as a reference is <https://en.wikipedia.org/wiki/List_of_mathematical_symbols>. This work are still on going, probably current version are not complete yet, but we will keep it updated as soon as we can. 

###Contents
* [Equals notation `=`, `≈`, `≠`, `:=`](#equals) 
* [Square root and complex numbers `√`, `i`](#sqrt_complex)
* [Dot and cross products `·`, `×`, `∘`](#dot_cross)
* [Sigma `Σ`](#sigma)
* [Capital Pi `Π` ](#cap_pi)
* [Pipes `||` ](#pipes)
	* [Absolute Value]()
	* [Euclidean Norm]()
	* [Determinant]()
* [Hat - unit vector]()
* [Element of `∈`, `∉`]()
* [Common number  sets `ℝ`, `ℤ`, `ℚ`, `ℕ`]()
* [Functions `ƒ`]()
	* [Piecewise function]()
	* [Common function]()
	* [Function Notation `↦`, `→`]()
* [Prime `′`]()
* [Floor and ceiling `⌊`, `⌉`]()
* [Arrows]()
	* [Material Implications `⇒`, `→`]()
	* [Equality `<`, `≥`, `≫`]()
	* [Conjunction & disjunction `∧`, `∨`]()
* [Logical negation `¬`, `~`, `!`]()
* [More]()


###Equals
```
#equality 
2 == 2:
#or 
2 is 2:

#inequality
2 != 2:
#or
2 is not 2:

#almost equal
#abs(a - b) < epsilon 
import math 
abs(math.PI - 3.14) < 0.00001

#definition
#we can use variable as a definition
#var_a := 2kj

var_a = 2 * k * j

```


###Square Root and Complex Numbers
```
#square root
#\sqrt{x^2} = x
import math
math.sqrt(9)


#complex number
#we can easily put i or j to make it imaginary or use cmath
1j * 1j = (-1 + 0j)

#or 

import cmath
cmath.sin(2 + 3j)  
```



###Dot and cross products

###Sigma

###Capital pi

###Pipes

###Hat

###ELement of

###Common number sets 

###Functions

###Prime

###Floor and ceiling

###Arrows

###Logical negation

###More