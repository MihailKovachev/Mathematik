> [!IMPORTANT] Nullstellensatz
> Eine Zahl $z_0 \in \mathbb{C}$ ist genau dann eine [Nullstelle](Nullstelle.md) des [Polynoms](../Polynom.md) $A(z)$, wenn $A(z)$ durch $(z-z_0)$ [teilbar](../Polynomdivision/Polynomdivision.md) ist.
> > [!CHECK]- Beweis
> > Wir müssen beide Richtungen beweisen.
> > 
> > Zuerst sei $A(x)$ durch $(x-p)$ teilbar. Dann gibt es ein Polynom $Q(x)$ derart, dass
> > $$A(x) = (x-p)Q(x)$$
> > Wenn wir $x$ durch $p$ ersetzen, erhalten wir
> > $$A(p) = (p-p)Q(x) = 0\cdot Q(x) = 0$$
> > Also ist $p$ eine Nullstelle von $A(x)$.
> > 
> > Sei umgekehrt $p$ eine Nullstelle von $A(x)$, d.h. $A(p) = 0$. Nach Bézouts Satz ist der Rest $R$ bei der Division von $A$ durch $(x-p)$ gleich $A(p)$, also
> > $$R = A(p) = 0$$
> > Das heißt, $A(x)$ lässt sich folgendermaßen darstellen:
> > $$A(x) = (x-p)Q(x) + 0 = (x-p)Q(x)$$
> > Also ist $A(x)$ durch $(x-p)$ teilbar.
> 
> > [!DANGER] Definition: $k$-fache Nullstelle
> > Ist $A(z)$ durch $(z-z_0)^k$ aber nicht durch $(z-z_0)^{k+1}$ teilbar, so heißt $z_0$ eine $k$**-fache Nullstelle** des Polynoms $A$.