>[!DEFINITION] Definition: Totale Differenzierbarkeit
>Seien $O\subseteq\mathbb{R}^n$ [offen](../../../../Topologie/Offene%20Menge.md) und $f: O\to\mathbb{R}^m$ eine [Funktion](../Reelle%20Funktion%20mehrerer%20Veränderlicher.md).
>
>Die Funktion $f$ heißt **total differenzierbar in** $\vec{a}\in O$, falls es eine [lineare Transformation](../../../../Lineare%20Algebra/Abstrakte%20lineare%20Algebra/Lineare%20Transformationen/Lineare%20Transformation.md) $L: \mathbb{R}^n\to\mathbb{R}^m$ gibt, sodass
>$$\lim_{\vec{h}\to\vec{0}}\frac{f(\vec{a}+\vec{h})-f(\vec{a})-L(\vec{a})}{||\vec{h}||}=\vec{0}$$
>
>Ist $f$ in jedem $\vec{a}\in O$ total differenzierbar, so heißt $f$ **total differenzierbar auf** $O$.
>
>>[!DEFINITION] Definition: Totales Differential
>>Das **totale Differential** von $f$ ist die (im Allgemeinen von $\vec{a}$ abhängige) [lineare Transformation](../../../../Lineare%20Algebra/Abstrakte%20lineare%20Algebra/Lineare%20Transformationen/Lineare%20Transformation.md) $L$.
>>>[!NOTATION] Bezeichnung
>>>$$\mathrm{d}f$$
>>
>>>[!THEOREM] Satz: Darstellungsmatrix des totalen Differential
>>>Die [Jacobi-Matrix](Jacobi-Matrix.md) $Df(\vec{a})$ ist die [Darstellungsmatrix](../../../../Lineare%20Algebra/Abstrakte%20lineare%20Algebra/Lineare%20Transformationen/Matrizendarstellung.md) des totalen Differentials bezüglich der [Standardbasen](../../../../Lineare%20Algebra/Vektoren%20als%20Matrizen/Reelle%20Vektoren/Standardbasis.md) von $\mathbb{R}^n$ und $\mathbb{R}^m$.
>>>>[!PROOF]- Beweis

