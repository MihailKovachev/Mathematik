>[!DEFINITION] Definition: Doppel-Riemann-Summe
>Seien $R: [a;b]\times [c;d]\subseteq\mathbb{R}^2$ ein Rechteck und $f:R\to\mathbb{R}$ ein [Skalarfeld](../Skalarfeld.md).
>
>Zerlege $[a;b]$ in $m$ Intervallen $[x_{i-1}; x_i]$ mit der Länge $\Delta x = \frac{b-a}{m}$. 
>Zerlege $[c;d]$ in $n$ Intervallen mit der Länge $\Delta y = \frac{d-c}{n}$.
>
>Aus diesen Zerlegungen ergeben sich kleinere Rechtecke $R_{ij} = \{(x,y)\mid x_{i-1} \le x \le x_i, y_{j-1} \le y \le y_j\}$ mit dem Flächeninhalt $\Delta A = \Delta x \Delta y$.
>
>Für jede konrekete Wahl von $x_{ij}^\ast$ und $y_{ij}^\ast$ mit $(x_{ij};y_{ij})$ entsteht eine **Doppel-Riemann-Summe** von $f$:
>
>$$\sum_{i=1}^m\sum_{j=1}^n f(x_{ij}^\ast, y_{ij}^\ast)\Delta A$$
>