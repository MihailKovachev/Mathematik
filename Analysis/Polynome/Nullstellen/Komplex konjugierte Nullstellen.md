> [!THEOREM] Satz: Komplex konjugierte Nullstellen
> Ist $z\in \mathbb{C}$ eine [Nullstelle](Nullstelle.md) eines [Polynoms](../Polynom.md) $P$ mit reellen Koeffizienten, so ist auch die zu $z$ [komplex konjugierte](../../../Komplexe%20Zahlen/komplexe%20Konjugation/Komplexe%20Konjugation.md) Zahl $\bar{z}$ eine Nullstelle von $P$.
> $$P(z)=0\implies P(\bar{z}) = 0$$
> > [!PROOF]- Beweis
> > $$a_nz^n + \cdots + a_1z + a_0 = 0$$
> > $$\overline{a_nz^n + \cdots + a_1z + a_0} = \bar 0$$
> > $$\overline{a_nz^n} + \cdots + \overline{a_1z} + \overline{a_0} = 0$$
> > $$\overline{a_n}\cdot\bar{z}^n + \cdots + \overline{a_1}\cdot\bar{z} + \overline{a_0} = 0$$
> > Für alle $a_j\in \mathbb{R}$ gilt $\overline{a_j} = a_j$, daher erhalten wir
> > $$a_n\bar{z}^n + \cdots + a_1\bar{z} + a_0 = 0$$