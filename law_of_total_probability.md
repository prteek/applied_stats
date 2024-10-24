# Law of total probability

[[Bayes theorem]] [[Conditional probability]]

Partition
A family B1,B2,B3... of events is called partition of the set Ω if
Bi ∩ Bj = ɸ if i ≠ j and U Bi = Ω

Each elementary event ⍵ ∊ Ω belongs to exactly one set in partition of Ω


Lemma 1.3 (Law of total probabilities)
Total probabilities for any events A and B such that 0 ≤ P(B) ≤ 1
P(A) = P(A ∩ Ω)
= P(A ∩ (B ∪ B'))
= P((A∩B) ∪ (A∩B'))
= P(A|B)*P(B) P(A|B')*P(B')

This is generally applicable to any number of Bi
P(A) = ΣP(A|Bi)*P(Bi)


#classnotes #psm #ch1 #probability #appliedstats
