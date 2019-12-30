## Probability

### Axioms of Probability
+ Random Experiments: flip coins, toss dice
+ Sample Space: S
+ Random Event: E
+ Operation of Random Events:
    1. Union: $\bigcup_{n=1}^{\infty}E_{n}$
    2. Intersection: $\bigcap_{n=1}^{\infty}E_{n}$
        1. null event: $\emptyset$
        2. mutually exclusive: $E \cap F=\emptyset$ 
    3. Complement: $E^{c}$
    4. Differenct: $E-F=E-EF$
+ Relation of Random Events: Venn diagram
    1. Contained(subset&superset): $E \subset F$ 
    2. Equal: $E=F \Leftrightarrow E \subset F\ and\ F \subset E$
+ Rules:
    1. Commutative: $E\cup F=F\cup E,E\cap F=F\cap E$
    2. Associative: $E\cup (F\cup G)=(E\cup F)\cup G,E\cap(F\cap G)= (E\cap F)\cap G$
    3. Distribution: $E\cup(F\cap G)=(E\cap F)\cap(E\cap G),E\cap(F\cup F)=(E\cup F)\cap(E\cup G)$
    4. DeMorgan: $(\bigcup_{i=1}^{n} E_i)^c=\bigcap_{i=1}^n E^c_i,(\bigcap_{i=1}^n E_i)^c=\bigcup_{i=1}^n E_i^c$
+ Definition:  
    $\quad \forall E\subset S,\exists P(E)\ st. following\ 3 \ axioms:$  
    1. $0\leq P(E)\leq1$
    2. $P(S)=1$
    3. $P(\bigcup_{i=1}^\infty E_i)=\sum_{i=1}^\infty P(E_i)$<br>
    We refer to $P(E)$ as the probability of the event E.
+ Propositions
    1. $P(\emptyset)=0$
    2. $P(\bigcup_{i=1}^nE_i)=\sum_{i=1}^n P(E_i)$
    3. $P(E^c)=1-P(E)$
    4. $P(E-F)=P(E)-P(EF)$
    5. $P(E\cup F)=P(E)+P(F)-P(EF)$
        1. Equation: $P(\bigcup_{i=1}^n E_i)$
        2. Inequation: 
+ Next
    1. $P(EF)=P(E)\cdot P(F)$