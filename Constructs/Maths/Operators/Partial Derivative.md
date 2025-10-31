---
tags:
  - math
aliases:
  - ∂
---
A [[Derivative]] of a single variable within a multivariable function. The symbol ∂ is effectively the same thing as d in [[Mathematical Notations#Leibnitz|Leibnitz Notation]], simply representing a partial. 

## Taking a Partial Derivative
To take a partial derivative, you effectively treat the variables other than the one you are differentiating as a constant, and derive for the one in question. 

## Formal Definition
The formal definition is very similar to the formal definition of the derivative. You just leave the extra variable alone, and measure change only in one at a time. 
$$
\frac{\partial f}{\partial x}(a,b)=\lim_{ h \to 0 } \frac{f(a+h, b) - f(a,b)}{h}
$$
## Higher Order Partial Derivatives 
Second Derivatives branch out, as with each derivative, you have the choice once again, of which derivative you should take. However, in all cases that do not violate [[Schwarz's Theorem]], a higher order derivative will be equal to any other higher order derivative with the same number of partials per variable. 
![[{7234C98A-3117-4DF1-8412-30155EB5F357}.png]]

