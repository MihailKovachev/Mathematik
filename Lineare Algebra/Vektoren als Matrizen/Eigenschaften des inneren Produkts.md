> [!IMPORTANT] Satz: Hermitesch
> Für das [Skalarprodukt](Skalarprodukt.md) zwei komplexer Vektoren $\vec{u} \in \mathbb{C}^{1\times n}$ und $\vec{v} \in \mathbb{C}^{n\times 1}$ gilt
> $$\vec{u}\cdot\vec{v} = \overline{\vec{v}\cdot\vec{u}}$$
> > [!IMPORTANT] Satz: Symmetrie für reelle Vektoren
> > Im Falle reeller Vektoren $\vec{u} \in \mathbb{R}^{1\times n}$ und $\vec{v} \in \mathbb{R}^{n\times 1}$ gilt
> > $$\vec{u}\cdot\vec{v} = \vec{v}\cdot\vec{u}$$
> 
> > [!CHECK]- Beweis
> > Dies folgt direkt aus der Definition des inneren Produkts.

> [!IMPORTANT] Satz: Distributivität
> Distributivität I: 
> - Für alle $\vec{u},\vec{v} \in \mathbb{C}^{1\times n}$ und $\vec{w}\in\mathbb{C}^{n\times 1}$ gilt
> $$(\vec{u} + \vec{v})\cdot\vec{w} = \vec{u}\cdot\vec{w}+\vec{v}\cdot\vec{w}$$
> 
> Distributitvität II: 
> - Für alle $\vec{u}\in\mathbb{C}^{1\times n}$ und $\vec{v},\vec{w}\in\mathbb{C}^{n\times 1}$ gilt
> $$\vec{u}\cdot(\vec{v}+\vec{w}) = \vec{u}\cdot\vec{v} + \vec{u}\cdot\vec{w}$$
> 
> > [!CHECK]- Beweis
> > Für Distributivität I betrachten wir die Definition des Skalarsprodukts
> > $$(\vec{u} + \vec{v}) \cdot \vec{w} = \begin{bmatrix}u_1 + v_1 & \cdots & u_n + v_n\end{bmatrix}\cdot\begin{bmatrix}w_1 \\ \vdots \\ w_n\end{bmatrix} = (u_1 + v_1)w_1 + \cdots + (u_n + v_n)w_n = \sum_{i=1}^n (u_i + v_i)w_i$$
> > $$\sum_{i=1}^n (u_i + v_i)w_i = \sum_{i=1}^n u_iw_i + \sum_{i=1}^n v_iw_i = \vec{u}\cdot\vec{w} + \vec{v}\cdot\vec{w}$$
> > Der Nachweis für Distributivität II ist analogisch.