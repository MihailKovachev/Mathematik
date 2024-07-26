> [!DANGER] Definition: Multiplikation von Matrizen
> Das Produkt zweier Matrizen $A = (a_{ij}) \in K^{m\times n}$ und $B = (b_{jk}) \in K^{n\times p}$ ist eine Matrix $A\cdot B = \left(\sum_{j=1}^n a_{ij}b_{jk}\right)_{ik} \in K^{m\times p}$, die anhand der [Skalarprodukt](../../Vektoren%20als%20Matrizen/Skalarprodukt.md) für Vektoren definiert wird:
> $$A\cdot B = \begin{bmatrix}\textemdash & \vec{a}_1 & \textemdash \\ \textemdash & \vdots & \textemdash \\ \textemdash & \vec{a}_m & \textemdash \end{bmatrix}\begin{bmatrix}\vert & \vert & \vert \\ \vec{b}_1 & \cdots & \vec{b}_p \\ \vert & \vert & \vert\end{bmatrix} \overset{\text{def}}{=} \begin{bmatrix}\vec{a}_1\cdot\vec{b}_1 & \cdots & \vec{a}_1\cdot\vec{b}_p \\ \vdots & \ddots & \vdots \\ \vec{a}_m\cdot\vec{b}_1 & \cdots & \vec{a}_m\cdot\vec{b}_p\end{bmatrix}$$
> - Die Zeilen der Matrix $A$ werden durch [Zeilenvektoren](../../Vektoren%20als%20Matrizen/Zeilenvektor.md) $\vec{a}_1, \cdots, \vec{a}_m$ dargestellt und die Spalten von $B$ werden durch [Spaltenvektoren](../../Vektoren%20als%20Matrizen/Spaltenvektor.md) $\vec{b}_1,\cdots,\vec{b}_p$ repräsentiert.
> - Der Eintrag in der $i$-ten Zeile und der $j$-ten Spalte in der Ergebnismatrix ist das Skalarprodukt der $i$-ten Zeile von $A$ mit der $j$-ten Spalte von $B$.
> $$(A\cdot B)_{ij} \overset{\text{def}}{=} \vec{a}_i \cdot \vec{b}_j$$
> 
> > [!NOTE] Notiz
> > Damit $A$ und $B$ multipliziert werden können, muss die Anzahl der Spalten von $A$ gleich der Anzahl der Zeilen von $B$ sein.
>
> > [!NOTE] Notiz
> > Das Produkt $A\cdot B$ hat so viele Zeilen wie $A$ und so viele Spalten wie $B$.

> [!DANGER] Definition: Potenzieren einer Matrix
> Für jede [quadratische Matrix](../Matrix.md) $A\in K^{n\times n}$ und jedes $k \in \mathbb{N}$ wird das **Potenzieren** folgendermaßen definiert:
> $$\begin{align}&A^0 \overset{\text{def}}{=} I_n \\ &A^k \overset{\text{def}}{=} \underset{k \text{-mal}}{\underbrace{A\cdot A \cdots A}}\end{align}$$