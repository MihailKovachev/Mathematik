>[!DEFINITION] Definition: Konvergenz einer Funktion mehrerer Veränderlicher
>Eine [Funktion](Reelle%20Funktion%20mehrerer%20Veränderlicher.md) $f: D \subseteq \mathbb{R}^n \to \mathbb{R}^m$ mit [Komponentenfunktionen](Reelle%20Funktion%20mehrerer%20Veränderlicher.md) $f_1,\cdots,f_m: D \to \mathbb{R}$ heißt **konvergent gegen** $\vec{L} = \begin{bmatrix}L_1 & \cdots & L_m\end{bmatrix}^\mathsf{T} \in \mathbb{R}^m$ **für** $\vec{x}\to \vec{a}$, falls $f_1,\cdots,f_m$ gegen jeweils $L_1,\cdots,L_m$ für $\vec{x}\to\vec{a}$ [konvergieren](Skalarfelder/Konvergenz%20von%20Skalarfeldern.md).
>
>$$\lim_{\vec{x} \to \vec{a}} f(\vec{x}) \overset{\text{def}}{=} \begin{bmatrix}\displaystyle \lim_{\vec{x} \to \vec{a}} f_1(\vec{x}) \\ \vdots \\ \displaystyle \lim_{\vec{x} \to \vec{a}} f_m(\vec{x}) \end{bmatrix} = \begin{bmatrix}L_1 \\ \vdots \\ L_m\end{bmatrix} = \vec{L}$$
>
>Man nennt $\vec{L}$ den **Grenzwert** von $f$ **für** $\vec{x} \to \vec{a}$.