> [!DEFINITION] Definition: Differenzierbarkeit
> Eine [Funktion](../Funktionen/Funktion.md) $f: D\subseteq \mathbb{R}\to\mathbb{R}$ heißt **differenzierbar im Punkt** $x_0\in D$ falls
> $$\exists \lim_{\Delta x\to 0} \frac{f(x_0+\Delta x) - f(x_0)}{\Delta x} = c \in \mathbb{R}$$
> 
> > [!DEFINITION] Definition: Ableitung
> > Man nennt $c$ die **Ableitung** von $f$ an der Stelle $x_0$.
> > > [!NOTATION] Bezeichnung
> > > $$f'(x_0) \qquad \frac{\mathrm{d}f}{\mathrm{d}x}(x_0)$$
> >
>
> Die Funktion $f$ heißt **differenzierbar auf** $D$, falls $f$ in allen $x \in D$ differenzierbar ist.
> > [!DEFINITION] Definition: Ableitungsfunktion
> > Die **Ableitungsfunktion** $f': D \to \mathbb{R}$ ist diejenige Funktion, die jedem $x_0\in D$ die Ableitung von $f$ in $x_0$ zuordnet.
> > > [!NOTATION] Bezeichnung
> > > $$f': D \to \mathbb{R}$$
> > > $$\frac{\mathrm{d}f}{\mathrm{d}x}: D \to \mathbb{R}$$

> [!DEFINITION] Definition: k-mal (stetig) differenzierbar
> Auch die Ableitungsfunktionen können differenzierbar sein und eigene Ableitungen besitzen.
> 
> Eine [Funktion](../Funktionen/Funktion.md) $f:D\subseteq\mathbb{R}\to\mathbb{R}$ heißt $k$**-mal (stetig) differenzierbar**, falls ihre $k$-te [Ableitung](Ableitung%20und%20Differenzierbarkeit.md) existiert (und stetig ist).
>> [!NOTATION] Bezeichnung: Höhere Ableitungsfunktionen
>> $$f \,\,\,\,\,\, f' \,\,\,\,\,\, f'' \,\,\,\,\,\, f''' \,\,\,\,\,\, f^{\text{IV}} \,\,\,\,\,\, f^{\text{V}} \,\,\,\,\,\, f^{\text{VI}} \,\,\,\,\,\, \cdots \qquad f^{(n)}$$
>> $$f \,\,\,\,\,\, \frac{df}{dx}\,\,\,\,\,\,\frac{d^2f}{dx^2}\,\,\,\,\,\, \frac{d^3f}{dx^3}\,\,\,\,\,\, \frac{d^4f}{dx^4}\,\,\,\,\,\, \frac{d^5f}{dx^5}\,\,\,\,\,\, \frac{d^6f}{dx^6}\,\,\,\,\,\, \cdots \qquad \frac{\mathrm{d}^nf}{\mathrm{d}x^n}$$