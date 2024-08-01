> [!DEFINITION] Definition: Multiplikation von Matrizen
> Das **Produkt** zweier [Matrizen](../Matrix.md) $A \in K^{m\times n}$ und $B \in K^{n\times p}$ ist eine Matrix $A\cdot B \in K^{m\times p}$:
> $$A\cdot B = \begin{bmatrix}a_{11} & \cdots & a_{1n} \\ \vdots & \ddots & \vdots \\ a_{m1} & \cdots & a_{mn} \end{bmatrix}\begin{bmatrix}b_{11} & \cdots & b_{1p} \\ \vdots & \ddots & \vdots \\ b_{n1} & \cdots & b_{np} \end{bmatrix}\overset{\text{def}}{=} \begin{bmatrix} c_{11} & \cdots & c_{1p} \\ \vdots & \ddots & \vdots \\ c_{m1} & \cdots & c_{mp}\end{bmatrix}$$
> mit
> $$c_{ij} \overset{\text{def}}{=} \sum_{k=1}^n a_{ik}b_{kj}$$
> > [!QUOTE] Erklärung zur Definition
> > Den Eintrag $c_{ij}$ in der $i$-ten Zeile under der $j$-ten Spalte, erhält man, indem man den $k$-ten Eintrag in der $i$-ten Zeile von $A$ mit dem $k$-ten Eintrag in der $j$-ten Spalte von $B$ multipliziert und diese Produkte summiert.
> 
> > [!THEOREM] 
> > Damit $A$ und $B$ multipliziert werden können, muss die Anzahl der Spalten von $A$ gleich der Anzahl der Zeilen von $B$ sein.
>
> > [!THEOREM] 
> > Das Produkt $A\cdot B$ hat so viele Zeilen wie $A$ und so viele Spalten wie $B$.
> 
> > [!NOTE] Schreibweise
> > Oft wird das Produkt zu nur $AB$ verkürzt.

> [!DEFINITION] Definition: Potenzieren einer Matrix
> Für jede [quadratische Matrix](../Matrix.md) $A\in K^{n\times n}$ und jedes $k \in \mathbb{N}$ wird das **Potenzieren** folgendermaßen definiert:
> $$\begin{align}&A^0 \overset{\text{def}}{=} I_n \\ &A^k \overset{\text{def}}{=} \underset{k \text{-mal}}{\underbrace{A\cdot A \cdots A}}\end{align}$$