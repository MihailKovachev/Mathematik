> [!THEOREM] Satz: Bézouts Satz über den Rest der Polynomdivision
> Bei der [Division](Polynomdivision.md) vom [Polynom](../Polynom.md) $A(x)$ durch $B(x) = x-p$ ist der Rest $R$ eine Zahl mit $R = A(p)$.
> > [!PROOF]- Beweis
> > Der Grad von $B(x)$ ist 1 und daher ist der Grad von dem Rest Null, da nach Definition $\deg (R) \lt \deg (B)$ ist. Das heißt, das Polynom $R(x)$ ist eigentlich nur eine Zahl $R$. Dann gilt
> > $$A(x) = (x-p)Q(x) + R$$
> > Wenn wir $x$ durch $p$ ersetzen, erhalten wir
> > $$A(p) = (p-p)Q(x) + R =0\cdot Q(x) + R = R$$
