> [!IMPORTANT] Satz: Größenlimit für linear unabhängige Mengen
> Jede Menge $M$ [linear unabhängiger](Lineare%20Unabhängigkeit.md) Vektoren aus einem [Vektorraum](Abstrakter%20Vektorraum.md) $(V,K,+,\cdot)$ enthält höchstens so viele Elemente wie die [Dimension](Basis/Dimension.md) des Vektorraums.
> $$|M|\le \dim (V)$$
> 
> > [!CHECK]- Beweis
> > Sei $B = \{\mathbf{v}_1,\cdots,\mathbf{v}_n\}$ eine [Basis](Basis/Basis.md) des Vektorraums und $M = \{\mathbf{u}_1,\cdots,\mathbf{u}_m\}$ eine Menge linear unabhängiger Vektoren. Nach dem [Steinitzschen Austauschsatz](Basis/Der%20Steinitzsche%20Austauschsatz.md) kann $M$ durch $n-m$ Vektoren aus $B$ zu einer Basis ergänzt werden. Daher muss $n-m$ eine nichtnegative Zahl sein, also
> > $$n-m\ge 0 \implies m\lt n$$
> 
> > [!IMPORTANT] Folgerung
> > Jede linear unabhängige Menge eines [endlich erzeugbaren](Erzeugendensystem.md) Vektorraums hat endlich viele Elemente.
> > > [!CHECK]- Beweis
> > > Angenommen, es gäbe eine linear unabhängige Menge $M_\infty$ mit unendlich vielen Elementen. Es gibt dann eine Teilmenge $M_\infty'$ von $M_\infty$ mit $\dim(V) + 1$ Elementen, die alle linear unabhängige Vektoren sind. Aber das widerspricht dem Größenlimit.