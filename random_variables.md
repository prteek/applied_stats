# Random variables

[[Discrete random variables]]
[[Continuous random variables]]

After an experiment is done and outcome ⍵∊Ω is known, random variable X is a real valued mapping ⍵∊Ω into ℝ or some subset of ℝ

Additionally the variable needs to have a property called Measurability which depends on the σ field F

The probability function
P(X<=x) = P({⍵∊Ω: X(⍵) <= x})
where P : F -> [0,1]
Domain of ℙ (Density function) is in F

More formally
Definition 1.12
A random variable is a function X: Ω->ℝ with the property that {⍵∊Ω: X(⍵) <= x} ∊ F
for each x ∊ ℝ. Such a function is said to be F measurable. It means that its values can be “predicted” or determined based on the information contained in the σ-field F

Intuition Behind F-measurability:

Think of a σ-field (denoted F) as a collection of events that represents the information you have.
A random variable  X  is F-measurable if you can determine whether  X  takes certain values or falls within specific ranges using only the information in F.



[[Distribution functions]]

#appliedstats #classnotes #psm #ch1
#probability
