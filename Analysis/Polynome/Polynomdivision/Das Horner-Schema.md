> [!ALGORITHM] Algorithmus: Das Horner-Schema
> Das Horner-Schema ist ein Algorithmus, mit dem man leicht ein [Polynom](../Polynom.md) $A(x)$ durch ein Polynom $B(x)$ von Grad eins [dividieren](Polynomdivision.md) kann.
> 
> Jedes Polynom $B(x)$ von Grad eins kann man als $B(x) = x - p$ schreiben und da $\deg(B) = 1$ ist, muss der Rest $R$ einfach eine Zahl sein, denn $\deg (R) \lt \deg(B) \implies \deg (R) = 0$. Dann haben wir
> $$A(x) = (x-p)Q(x) + R$$
> Um die Koeffizienten von $Q$ und den Rest $R$ zu finden, können wir die folgende Tafel benutzen:
> 
> ||$a_n$|$a_{n-1}$|$\cdots$|$a_1$|$a_0$|
> |:--:|:--:|:--:|:--:|:--:|:--:|
> |$p$|$q_{n-1} = a_n$|$q_{n-2} = pq_{n-1} + a_{n-1}$|$\cdots$|$q_0 = pq_1 + a_1$|$R = pq_0 + a_0$|
> 
> Diese berechnen wir von links nach rechts.
> 
> Der erste Koeffizient $q_{n-1}$ von $Q(x)$ ist also gleich dem ersten Koeffizienten von $A(x)$, d.h. $q_{n-1} = a_n$.
> 
> Für alle anderen Koeffizienten von $Q(x)$ gilt $q_i = pq_{i+1} + a_{i-1}$.
> 
> Die letzte Berechnung liefert uns den Rest $R$
> > [!example]- Beispiel
> > Sei $A(x) = 2x^5+3x^3-11x^2+6$ und $B(x) = x-3$. Erstellen wir nun das Horner-Schema:
> > 
> > ||$2$|$0$|$3$|$-11$|$0$|$6$|
> > |:--:|:--:|:--:|:--:|:--:|:--:|:--:|
> > |$p = 3$|||||||
> > 
> > Dieses füllen wir Schritt für Schritt aus.
> > 
> > ||$2$|$0$|$3$|$-11$|$0$|$6$|
> > |:--:|:--:|:--:|:--:|:--:|:--:|:--:|
> > |$p = 3$|2||||||
> > 
> > ||$2$|$0$|$3$|$-11$|$0$|$6$|
> > |:--:|:--:|:--:|:--:|:--:|:--:|:--:|
> > |$p = 3$|2|6|||||
> > 
> > ||$2$|$0$|$3$|$-11$|$0$|$6$|
> > |:--:|:--:|:--:|:--:|:--:|:--:|:--:|
> > |$p = 3$|2|6|21||||
> > 
> > ||$2$|$0$|$3$|$-11$|$0$|$6$|
> > |:--:|:--:|:--:|:--:|:--:|:--:|:--:|
> > |$p = 3$|2|6|21|52|||
> > 
> > ||$2$|$0$|$3$|$-11$|$0$|$6$|
> > |:--:|:--:|:--:|:--:|:--:|:--:|:--:|
> > |$p = 3$|2|6|21|52|156||
> > 
> > ||$2$|$0$|$3$|$-11$|$0$|$6$|
> > |:--:|:--:|:--:|:--:|:--:|:--:|:--:|
> > |$p = 3$|2|6|21|52|156|474|
> > 
> > Letztendlich lesen wir das Ergebnis ab:
> > $$R = 474$$
> > $$Q(x) = 2x^4 + 6x^3 + 21x^2 + 52x + 156$$