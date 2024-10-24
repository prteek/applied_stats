# Distribution of monotone RV

Monotonous function y = g(x) can be either
Non decreasing (derivative +ve)
Non increasing (derivative -ve)

They can also be
Strictly increasing (or decreasing) ; g^-1 is a point set {y}
Not strictly increasing (or decreasing) ; g^-1 is a set but for single y ∊ Yi has multiple x ∊ Xi

consider X~Fx(X) ; fx(X)
Y = g(X) ; Let g(X) is strictly increasing (unique inverse)

Fy(Y) = P(Y ≤ y)
= P(g(X) ≤ y)
= P(X ≤ g^-1(y))
= Fx(g^-1(y))

fy(Y) = d(Fy(Y))/dy
= d(Fx(g^-1(y)))/dy
= d(g^-1(y))/dy * fx(g^-1(y))

for g(X) strictly decreasing
Fy(Y) = 1 - Fx(g^-1(y))
fy(Y) = - ￼￼￼￼d(g^-1(y))/dy * fx(g^-1(y))

covering both cases
fy(Y) = | d(g^-1(y))/dy | * fx(g^-1(y))

The abs operator here ensures that fy is non negative since it is a probability distribution function.

Examples in Lecture notes and Casella Berger

#appliedstats #classnotes #psm #ch4 #probability 
