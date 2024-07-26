> [!IMPORTANT] Satz: Der Fundamentalsatz der Analysis (Teil I)
> Ist $f: [a;b] \to \mathbb{R}$ eine [stetige](../Grenzwerte%20von%20Funktionen/Stetigkeit/Stetigkeit.md) [Funktion](../Funktionen/Funktion.md), so ist $F: [a;b] \to \mathbb{R}$
> $$F(x) \overset{\text{def}}{=} \int_c^x f(t) \mathop{\mathrm{d}t}$$
>  für jedes $c\in [a;b]$ eine [Stammfunktion](Stammfunktion.md) von $f$.
>  
> > [!NOTE] Notiz: Geschlossene Form der Stammfunktionen
> > Dieser Satz bedeutet, dass jede stetige Funktion mindestens eine Stammfunktion hat. Diese Stammfunktion ist aber nicht in geschlossener Form angegeben und oft besteht keine solche Darstellung.
>  
> > [!CHECK]- Beweis
> > Laut der Definition der [Ableitung](../Differentiation/Ableitung%20und%20Differenzierbarkeit.md) müssen wir beweisen, dass
> > $$\lim_{\Delta x\to 0}\frac{F(x+\Delta x) - F(x)}{\Delta x} = f(x)$$
> >
> > 
> > Für alle $c, x_0,\Delta x \in [a;b]$ mit $x_0+\Delta x \in [a;b]$ gilt
> > $$\begin{align}F(x_0+\Delta x) - F(x_0) &= \int_c^{x_0+\Delta x} f(t)\mathop{\mathrm{d}t} - \int_c^{x_0} f(t)\mathop{\mathrm{d}t} \\ &= \int_c^{x_0+\Delta x} f(t)\mathop{\mathrm{d}t} + \int_{x_0}^c f(t)\mathop{\mathrm{d}t} \\ &= \int_{x_0}^c f(t)\mathop{\mathrm{d}t} + \int_c^{x_0+\Delta x} f(t)\mathop{\mathrm{d}t} \\ &= \int_{x_0}^{x_0+\Delta x}f(t) \mathop{\mathrm{d}t}\end{align}$$
> > 
> > Nach dem [Mittelwertsatz der Integralrechnung](Mittelwertsatz%20der%20Integralrechnung.md) besteht ein $\xi \in[x_0;x_0+\Delta x]$ derart, dass
> > $$\int_{x_0}^{x_0+\Delta x}f(t) \mathop{\mathrm{d}t} = f(\xi)(x_0 + \Delta x - x_0) = f(\xi)\cdot\Delta x$$
> > Daraus folgt
> > $$\frac{F(x_0+\Delta x) - F(x_0)}{\Delta x} = f(\xi)$$
> > Wir betrachten nun den [Limes](../Grenzwerte%20von%20Funktionen/Grenzwerte.md) für $\Delta x \to 0$.
> > $$\lim_{\Delta x \to 0}\frac{F(x_0+\Delta x) - F(x_0)}{\Delta x} = \lim_{\Delta x \to 0}f(\xi)$$
> > Die linke Seite ist einfach die Ableitung von $F$ im Punkt $x_0$.
> > Da $\xi$ zwischen $x_0$ und $\Delta x$ ist, gilt $\xi \to x_0$ für $\Delta x \to 0$. Das heißt
> > $$\lim_{\Delta x\to 0}f(\xi) = f(x_0)$$
> > Zusammen ergibt sich
> > $$\lim_{\Delta x \to 0}\frac{F(x_0+\Delta x) - F(x_0)}{\Delta x} = f(x_0)$$
> > Also
> > $$F'(x_0) = f(x_0)$$

> [!IMPORTANT] Satz: Der Fundamentalsatz der Analysis (Teil II)
> Ist $f: [a;b] \to \mathbb{R}$ eine [stetige](../Grenzwerte%20von%20Funktionen/Stetigkeit/Stetigkeit.md) [Funktion](../Funktionen/Funktion.md), dann gilt für jede beliebige [Stammfunktion](Stammfunktion.md) $F: [a;b] \to \mathbb{R}$ von $f$
> $$\int_a^b f(x) \mathop{\mathrm{d}x} = F(b) - F(a)$$
>
> > [!NOTE] Schreibweise
> > Oft schreibt man $F(b) - F(a)$ als $F(x)\Big|_a^b$.
> 
> > [!QUOTE] Bestimmte vs Unbestimmte Integrale
> > Dieser Satz liefert einen Weg zur Berechnenung von [bestimmten Integralen](Bestimmtes%20(Riemann-)Integral.md) anhand [unbestimmter Integrale](Unbestimmtes%20Integral.md).
> 
> > 
> 
> > [!CHECK]- Beweis
> > 