>[!THEOREM] Satz: Stetigkeit der Parameterintegrale
>Seien $R = [a;b] \times [c;d] \subset \mathbb{R}^2$ ein Rechteck und $f: R  \to \mathbb{R}$ ein [Skalarfeld](../Skalarfeld.md).
>
>Falls $f$ [stetig](../Stetigkeit%20von%20Skalarfeldern.md) auf $R$ ist, so sind die [Parameterintegrale](Parameterintegrale.md)
>- $\int_c^d f(x,y)\mathop{\mathrm{d}y}$ [stetig](../../../../Eindimensionale%20Analysis/Grenzwerte%20von%20Funktionen/Stetigkeit/Stetigkeit.md) auf $[a;b]$;
>- $\int_a^b f(x,y)\mathop{\mathrm{d}x}$ [stetig](../../../../Eindimensionale%20Analysis/Grenzwerte%20von%20Funktionen/Stetigkeit/Stetigkeit.md) auf $[c;d]$.
>
>>[!PROOF]- Beweis

>[!THEOREM] Satz: Leibniz-Regel
>Seien $R = [a;b] \times [c;d] \subset \mathbb{R}^2$ ein Rechteck und $f: R  \to \mathbb{R}$ ein [Skalarfeld](../Skalarfeld.md).
>
>Falls $f$ [stetig partiell differenzierbar](../Differentiation/Partielle%20Differenzierbarkeit.md) und $u,o$ [stetig differenzierbar](../../../../Eindimensionale%20Analysis/Differentiation/Ableitung%20und%20Differenzierbarkeit.md) sind, gelten für die [Ableitung](../../../../Eindimensionale%20Analysis/Differentiation/Ableitung%20und%20Differenzierbarkeit.md) der [Parameterintegrale](Parameterintegrale.md) von $f$
>
>$$\frac{\mathrm{d}}{\mathrm{d}x} \int_{u(x)}^{o(x)} f(x,y) \mathop{\mathrm{d}y} = \int_{u(x)}^{o(x)} \frac{\partial}{\partial x}f(x,y)\mathop{\mathrm{d}y} \,+\, f(x,o(x))\frac{\mathrm{d}}{\mathrm{d}x}o(x) - f(x, u(x))\frac{\mathrm{d}}{\mathrm{d}x}u(x)$$
>
>
>$$\frac{\mathrm{d}}{\mathrm{d}y} \int_{u(y)}^{o(y)} f(x,y) \mathop{\mathrm{d}x} = \int_{u(y)}^{o(y)} \frac{\partial}{\partial y}f(x,y)\mathop{\mathrm{d}x} \,+\, f(y,o(y))\frac{\mathrm{d}}{\mathrm{d}y}o(y) - f(y, u(y))\frac{\mathrm{d}}{\mathrm{d}x}u(y)$$
>
>>[!PROOF]- Beweis