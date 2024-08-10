>[!DEFINITION] Definition: Partielle Ableitung
>Sei $f:D\subseteq\mathbb{R}^n\to\mathbb{R}$ ein [Skalarfeld](Skalarfeld.md).
>
>Die **partielle Ableitung** von $f$ in $\vec{x}\in D$ bezüglich der Veränderlichen $x_i$ ist die [Richtungsableitung](Richtungsableitung.md) von $f$ in $\vec{x}$ in Richtung des $i$-ten [Vektors](../../../../../Lineare%20Algebra/Vektoren%20als%20Matrizen/Reelle%20Vektoren/Reeller%20Spaltenvektor.md) der [Standardbasis](../../../../../Lineare%20Algebra/Vektoren%20als%20Matrizen/Reelle%20Vektoren/Standardbasis.md) von $\mathbb{R}^n$, falls sie existiert.
>$$\lim_{h\to 0}\frac{f(\vec{x}+h\cdot\vec{e}_i)-f(\vec{x})}{h} = \lim_{h\to 0}\frac{f(x_1,\cdots,x_i+h,\cdots + x_n) - f(x_1,\cdots,x_i,\cdots, x_n)}{h}$$
>
>>[!NOTE] Bezeichnung
>>$$\frac{\partial f}{\partial x_i} (\vec{x}) \qquad  \frac{\partial}{\partial x_i} f(\vec{x})\qquad \partial_i f (\vec{x}) \qquad f_{x_i} (\vec{x}) \qquad f_{x_i}(\vec{x})$$
>
>Die [Funktion](Skalarfeld.md) $\partial_i f: D\to\mathbb{R}$, die jedem $\vec{x}\in D$ die partielle Ableitung von $f$ in $\vec{x}$ bezüglich $x_i$ zuordnet, ist auch als partielle Ableitung von $f$ bekannt.