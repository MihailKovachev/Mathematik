>[!DEFINITION] Definition: Hesse-Matrix
>Sei $f:D\subseteq\mathbb{R}^n\to\mathbb{R}$ ein [zweimal partiell differenzierbares](Höhere%20Ableitungen.md) [Skalarfeld](../Skalarfeld.md).
>
>Die **Hesse-Matrix** von $f$ in $\vec{x}\in D$ ist die $n\times n$ [quadratische Matrix](../../../../../Lineare%20Algebra/Matrizen/Quadratische%20Matrizen/Quadratische%20Matrix.md), die die [Gradienten](Gradient.md) der [ersten partiellen Ableitungen](Partielle%20Ableitung.md) von $f$ als Spalten enthält.
>$$H_f(\vec{x})\overset{\text{def}}{=} \begin{bmatrix}\vert & \vert & \vert \\ \nabla(\partial_1 f)(\vec{x}) & \cdots & \nabla(\partial_n f)(\vec{x}) \\ \vert & \vert & \vert \end{bmatrix} = \begin{bmatrix}\partial_1 \partial_1 f(\vec{x}) & \cdots & \partial_1\partial_n f(\vec{x}) \\ \vdots & \ddots & \vdots \\ \partial_n\partial_1 f(\vec{x}) & \cdots & \partial_n\partial_n f(\vec{x})\end{bmatrix}$$
>
>Der Eintrag in der $i$-ten Zeile und $j$-ten Spalte der Hesse-Matrix ist
>$$\frac{\partial^2}{\partial {x_i}\, \partial x_j} f(\vec{x})$$

>[!IMPORTANT] Satz: Symmetrie der Hesse-Matrix
>Die Hesse-Matrix ist [symmetrisch](../../../../../Lineare%20Algebra/Matrizen/Quadratische%20Matrizen/Symmetrische%20Matrix.md), falls $f\in C^2(D)$.
>>[!PROOF]- Beweis
>>Dies folgt aus dem [Vertauschbarkeitssatz von Schwarz](Vertauschbarkeitssatz%20von%20Schwarz.md)
