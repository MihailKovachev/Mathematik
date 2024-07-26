> [!DANGER] Definition: Längen (Betrag)
> Die **Länge** oder der **Betrag** eines [Vektors](Spaltenvektor.md) wird durch das [Skalarprodukt](Skalarprodukt.md) des Vektors definiert:
> $$|\vec{v}| \overset{\text{def}}{=} \sqrt{\vec{v}\cdot\vec{v}^{\mathrm{T}}}$$
> > [!NOTE] Notiz: Länge in 2 und 3 Dimensionen
> > Für Vektoren in 2 und 3 Dimensionen ist diese Definition äquivalent zu unserer intuitiven Vorstellung von Länge für Pfeilen. Sie ermöglicht uns aber, den Begriff der Länge auf höhere Dimensionen zu generalisieren.
> 
> > [!EXAMPLE]- Beispiel: Vektoren in 2 und 3 Dimensionen
> > Betrachten wir den Vektor $\vec{v} = \begin{bmatrix}3 & 4\end{bmatrix}$. Laut Definition wird seine Länge folgendermaßen berechnet:
> > $$|\vec{v}| = \sqrt{\vec{v}\cdot\vec{v}^\mathrm{T}} = \sqrt{\begin{bmatrix}3 & 4\end{bmatrix} \begin{bmatrix}3 \\ 4\end{bmatrix}} = \sqrt{3\cdot 3 + 4\cdot 4} = \sqrt{9 + 16} = \sqrt{25} = 5$$
> > Dieses Ergebnis stimmt mit dem Ergebnis, das wir durch den Satz des Pythagoras erhalten hätten, d.h. $|\vec{v}| = \sqrt{3^2 + 4^2} = 5$.
> > 
> > Ähnlicherweise betrachten wir jetzt den Vektor
> > $$\vec{u} = \begin{bmatrix}2 \\ 10 \\ 11\end{bmatrix}$$
> > Laut Definition wird sein Betrag folgendermaßen berechnet:
> > $$|\vec{u}| = \sqrt{\begin{bmatrix}2 \\ 10 \\ 11\end{bmatrix} \begin{bmatrix}2 & 10 & 11\end{bmatrix}} = \sqrt{2\cdot 2 + 10\cdot 10 + 11\cdot 11} = \sqrt{4 + 100 + 121} = \sqrt{225} = 15$$
> > Dieses Ergebnis stimmt mit dem Ergebnis, das wir durch den 3D-Satz des Pythagoras erhalten hätten, d.h. $|\vec{u}| = \sqrt{2^2 + 10^2 + 11^2} = 15$.