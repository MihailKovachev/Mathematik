>[!THEOREM] Satz: Linearität der Ableitungen von Kurven
>Für alle $\mu,\lambda \in \mathbb{R}$ und alle [Kurven](../Kurve.md) $\mathbf{u},\mathbf{v}:I\subseteq \mathbb{R}\to\mathbb{R}^n$ gilt
>$$\frac{\mathrm{d}}{\mathrm{d}t}[\lambda\,\mathbf{u}(t) + \mu\,\mathbf{v}(t)] = \lambda\,\mathbf{u}'(t) + \mu\,\mathbf{v}'(t)$$
>>[!PROOF]- Beweis

>[!THEOREM] Satz: Kettenregel
>Für die Ableitung der [Verkettung](../../../../../Mengenlehre/Abbildungen/Verkettung.md) einer [Funktion](../../../../Eindimensionale%20Analysis/Funktionen/Funktion.md)$f:I\subseteq\mathbb{R}\to\mathbb{R}$ mit einer [Kurve](../Kurve.md) $\mathbf{r}:f(I)\to\mathbb{R}^n$ gilt
>$$\frac{\mathrm{d}}{\mathrm{d}t}\mathbf{r}(f(t)) = f'(t)\,\mathbf{r}'(f(t))$$
>>[!PROOF]- Beweis

>[!THEOREM] Satz: Produktregel
>Für die [Ableitung](Ableitung%20von%20Kurvenparametrisierungen.md) des Produkts einer [reellwertigen Funktion](../../../../Eindimensionale%20Analysis/Funktionen/Funktion.md) $f:I\subseteq\mathbb{R}\to\mathbb{R}$ mit einer [Kurve](../Kurve.md) $\mathbf{r}:I\to\mathbb{R}^n$ gilt
>$$\frac{\mathrm{d}}{\mathrm{d}t}[f(t)\mathbf{r}(t)] = f'(t)\mathbf{r}(t) + \mathbf{r}'(t)f(t)$$
>>[!PROOF]- Beweis

>[!THEOREM] Satz: Ableitung des Skalarsprodukts
>Für die [Ableitung](Ableitung%20von%20Kurvenparametrisierungen.md) des [Skalarprodukts](../../../../../Lineare%20Algebra/Vektoren%20als%20Matrizen/Reelle%20Vektoren/Kanonisches%20Skalarprodukt.md) zweier [Kurven](../Kurve.md) $\mathbf{u},\mathbf{v}:I\subseteq \mathbb{R}\to\mathbb{R}^n$ gilt
>$$\frac{\mathrm{d}}{\mathrm{d}t}[\mathbf{u}(t)\cdot\mathbf{v}(t)] = \mathbf{u}'(t)\cdot \mathbf{v}(t) + \mathbf{u}(t)\cdot\mathbf{v}'(t)$$
>>[!PROOF]- Beweis

>[!THEOREM] Satz: Ableitung des Kreuzprodukts
>Für die [Ableitung](Ableitung%20von%20Kurvenparametrisierungen.md) des [Kreuzprodukts](../../../../../Lineare%20Algebra/Vektoren%20als%20Matrizen/Reelle%20Vektoren/Kreuzprodukt.md) zweier [Kurven](../Kurve.md) $\mathbf{u},\mathbf{v}:I\subseteq\mathbb{R}\to\mathbb{R}^n$ in $\mathbb{R}^3$ gilt
>$$\frac{\mathrm{d}}{\mathrm{d}t}[\mathbf{u}(t)\times \mathbf{v}(t)] = \mathbf{u}'(t)\times\mathbf{v}(t) + \mathbf{u}(t)\times\mathbf{v}'(t)$$
>
>>[!PROOF]- Beweis