> [!DEFINITION] Definition: Riemann-Summe
> Seien $f: [a,b]\to \mathbb{R}$ eine [Funktion](../../Funktionen/Funktion.md) auf dem abgeschlossenen Intervall $[a;b]\subset\mathbb{R}$ und $Z = (x_0,x_1,\cdots,x_n)$ eine Zerlegung von $[a;b]$.
> 
> Eine **Riemann-Summe** von $f$ über dem durch $Z$ zerlegten Intervall $[a;b]$ ist eine Summe der Form
> $$\sum_{i=1}^n f(x_i^\ast)\Delta x_i,$$
> wobei $\Delta x_i = (x_i - x_{i-1})$ und $x_i^\ast \in [x_{i-1};x_i]$.
> > [!NOTE] Wahl von $x_i^\ast$
> > Je nach der Wahl von $x_i^\ast$ erhält man verschiedene Riemann-Summen.
> 
> > [!DEFINITION]+ Definition: Linke Riemann-Summe
> > Eine **linke Riemann-Summe** ist eine Riemann-Summe mit 
> > $$x_i^\ast = x_{i-1}$$
> 
> > [!DEFINITION]+ Definition: Rechte Riemann-Summe
> > Eine **rechte Riemann-Summe** ist eine Riemann-Summe mit 
> > $$x_i^\ast = x_{i}$$
> 
> > [!DEFINITION]+ Definition: Riemann'sche Mittelpunksumme
> > Eine **Riemann'sche Mittelpunksumme** ist eine Riemann-Summe mit 
> > $$x_i^\ast = \frac{x_{i-1}+x_i}{2}$$
> 
> > [!DEFINITION]+ Definition: Riemann'sche Untersumme
> > Eine **Riemann'sche Untersumme** ist eine Riemann-Summe mit $x_i^\ast$ derart, dass
> > $$f(x_i^\ast) = \inf \{f(x) \mid x\in [x_{i-1};x_i]\}$$
> 
> > [!DEFINITION]+ Definition: Riemann'sche Obersumme
> > Eine **Riemann'sche Obersumme** ist eine Riemann-Summe mit $x_i^\ast$ derart, dass
> > $$f(x_i^\ast) = \sup \{f(x) \mid x\in [x_{i-1};x_i]\}$$
