>[!DEFINITION] Definition: Ableitung einer Kurve
>Eine [Kurvenparametrisierung](../Kurve.md) $\mathbf{r}: I \subseteq \mathbb{R} \to \mathbb{R}^n$ heißt **differenzierbar in** $t_0\in I$, falls der [Grenzwert](../Konvergenz%20von%20Kurvenparametrisierungen.md)
>
>$$\lim_{\Delta t_0 \to 0} \frac{\mathbf{r}(t+\Delta t)-\mathbf{r} (t_0)}{\Delta t}$$
>
>existiert. Dieser Grenzwert heißt **Ableitung** oder **Tangentenvektor** von $\mathbf{r}$ in $t_0 \in I.$
>
>>[!NOTATION] Bezeichnung
>>$$\mathbf{r}'(t_0)\qquad \dot{\mathbf{r}}(t_0) \qquad \frac{\mathrm{d}\mathbf{r}}{\mathrm{d}t}(t_0)$$
>
>Existiert die Ableitung für alle $t\in I$, so heißt $\mathbf{r}$ **differenzierbar auf** $D$.
>
>
>>[!THEOREM] Satz: Komponentenweise Differenzierbarkeit
>>Eine [Kurvenparametrisierung](../Kurve.md) ist genau dann differenzierbar in $t \in I$, wenn alle ihre [Komponentenfunktionen](../../Reelle%20Funktion%20mehrerer%20Veränderlicher.md) [differenzierbar](../../../../Eindimensionale%20Analysis/Differentiation/Ableitung%20und%20Differenzierbarkeit.md) in $t$ sind.
>>
>>>[!PROOF]- Beweis
>>>Es seien $f_1,\cdots,f_n$ die Komponentenfunktionen von $\mathbf{r}:I\subseteq\mathbb{R}\to\mathbb{R}^n$. Für $t\in I$ gilt dann
>>>$$\begin{align}\mathbf{r}'(t) = \lim_{\Delta t\to 0}\frac{\mathbf{r}(t+\Delta t)-\mathbf{r}(t)}{\Delta t} &= \lim_{\Delta t\to 0} \frac{1}{\Delta t} \left( \begin{bmatrix} f_1(t+\Delta t) \\ \vdots \\ f_n(t+\Delta t)\end{bmatrix} - \begin{bmatrix} f_1(t) \\ \vdots \\ f_n( t)\end{bmatrix} \right) \\ &= \lim_{\Delta t\to 0} \begin{bmatrix} \frac{f_1(t+\Delta t) - f_1(t)}{\Delta t} \\ \vdots \\ \frac{f_n(t+\Delta t) - f_n(t)}{\Delta t} \end{bmatrix}\\ &= \begin{bmatrix} \lim_{\Delta t\to 0} \frac{f_1(t+\Delta t) - f_1(t)}{\Delta t} \\ \vdots \\ \lim_{\Delta t\to 0} \frac{f_n(t+\Delta t) - f_n(t)}{\Delta t} \end{bmatrix} \\ &= \begin{bmatrix}f_1'(t) \\ \vdots \\ f_n'(t)\end{bmatrix}\end{align}$$

>[!DEFINITION] Definition: Stetige Differenzierbarkeit
>Eine [Kurve](../Kurve.md) heißt $k$**-mal (stetig) differenzierbar**, falls alle ihre [Komponentenfunktionen](../../Reelle%20Funktion%20mehrerer%20Veränderlicher.md) $k$-mal [differenzierbar](../../../../Eindimensionale%20Analysis/Differentiation/Ableitung%20und%20Differenzierbarkeit.md) sind (und die entsprechenden $k$-ten Ableitungen stetig sind).

>[!DEFINITION] Definition: Stückweise (stetige) Differenzierbarkeit
>Eine [Kurve](../Kurve.md) $\gamma:I\subseteq \mathbb{R}\to\mathbb{R}^n$ heißt **stückweise (stetig) differenzierbar**,  falls das Intervall $I$ so aufgeteilt werden kann, dass alle [Komponentenfunktionen](../../Reelle%20Funktion%20mehrerer%20Veränderlicher.md) von $\gamma$ auf jedem Teilintervall stetig differenzierbar sind??