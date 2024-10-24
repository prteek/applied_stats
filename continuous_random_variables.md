# Continuous random variables

[[Random variables]] [[Discrete random variables]]

X is a continuous RV if its distribution function can be expressed as
Fx(X) = ∫(-inf,x) fx(s) ds for x ∊ ℝ
for some integrable function fx: R -> [0, inf) called the probability density function of X
The distribution function of a continuous RV is certainly continuous (it is 'absolutely continuous').
Range of X, Rx = {x ∊ ℝ : fx(x) > 0}

When we refer to a continuous random variable X we are asserting that the distribution function of the random variable rather than the random variable X itself is continuous.
The density function fx(.) is not uniquely prescribed.

Lemma 2.2
If X has a density function fx(.) then  
1. fx(x) ≥ 0  
2. ∫(-inf, inf) fx(x) dx = 1  
3. ℙ(a < X ≤ b) = ∫(a,b) fx(x) dx  
4. ℙ(X=x) = 0, for all x ∊ ℝ  

#appliedstats #classnotes #psm #ch2
#probability
