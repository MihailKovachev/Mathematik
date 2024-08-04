> [!ALGORITHM] Algorithmus: Lösen von trennbaren GDGL erster Ordnung
> Wir betrachten die [Trennbare GDGL erster Ordnung](Trennbare%20GDGL%20erster%20Ordnung.md)
> $$N(y)\frac{\mathop{\mathrm{d}y}}{\mathop{\mathrm{d}x}} = M(x)$$
> 1. "Trenne" die Differenziale:
> $$N(y)\mathop{\mathrm{d}y}= M(x)\mathop{\mathrm{d}x}$$
> 2. Integriere beide Seiten:
> $$\int N(y)\mathop{\mathrm{d}y} = \int M(x)\mathop{\mathrm{d}x}$$
> 3. Erhalte die implizite Lösung
> $$\int N(y)\mathop{\mathrm{d}y} - \int M(x)\mathop{\mathrm{d}x} = c \qquad c\in\mathbb{R}$$
> 4. Falls möglich, versuche eine explizite Lösung zu finden.
> 
> > [!NOTE]- Notiz: "Trennen" der Differenziale
> > Eigentlich darf man die Ableitung nicht so trennen. Dieser Notationsmissbrauch ist aber eine nützliche Abkürzung des folgenden Verfahren.
> > $$N(y)\frac{\mathop{\mathrm{d}y}}{\mathop{\mathrm{d}x}} = M(x)$$
> > Integriere beide Seiten bezüglich $\mathop{\mathrm{d}x}$.
> > $$\int N(y)\frac{\mathop{\mathrm{d}y}}{\mathop{\mathrm{d}x}} \mathop{\mathrm{d}x}= \int M(x) \mathop{\mathrm{d}x}$$
> > Wende die [Substitutionsregel](../../../Integration/Unbestimmte%20Integrale/Integrationsregeln.md) an.
> > $$u = y(x) \implies \frac{\mathop{\mathrm{d}u}}{\mathop{\mathrm{d}x}} = y'(x) \implies \mathop{\mathrm{d}u} = \frac{\mathop{\mathrm{d}y}}{\mathop{\mathrm{d}x}} \mathop{\mathrm{d}x}$$
> > Daraus ergibt sich
> > $$\int N(u)\mathop{\mathrm{d}u} = \int M(x) \mathop{\mathrm{d}x}$$
> > Wenn wir $N(u)\mathop{\mathrm{d}u}$ zunächst Integrieren und dann wieder $y(x)$ für $u$ einsetzen, erhalten wir genau dasselbe Ergebnis, als hätten wir direkt $N(y)\mathop{\mathrm{d}y}$ integriert und die Abhängigkeit von $x$ ignoriert. Deshalb ersparen wir uns diese Substitution, um die Lösungen zu verkürzen.
> 
> > [!EXAMPLE]- Beispiel