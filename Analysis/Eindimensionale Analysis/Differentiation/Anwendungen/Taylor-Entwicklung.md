>[!DEFINITION] Definition: Taylor-Polynom
>Sei $f:I\subseteq\mathbb{R}\to\mathbb{R}$ eine $m$[-mal differenzierbare](../Höhere%20Ableitungen.md) [Funktion](../../Funktionen/Funktion.md).
>
>Das $m$-te **Taylorpolynom** von $f$ um den Entwicklungspunkt $a\in I$ ist
>$$T_{m,f,a}(x) \overset{\text{def}}{=} \sum_{k=0}^m\frac{f^{(k)}(a)}{k!} (x-a)^k$$
>
>>[!DEFINITION] Definition: Restglied
>>Das **Restglied** des Taylorpolynoms $T_{m,f,a}(x)$ ist
>>$$R_{m+1} \overset{\text{def}}{=} f(x) - T_{m, f, a}(x)$$
>>
>>>[!THEOREM] Satz: Darstellungen
>>>Ist $f$ auch $m+1$[-mal stetig differenzierbar](../Höhere%20Ableitungen.md), so lässt sich der Restglied folgendermaßen darstellen:
>>>- Lagrange'sche Darstellung - für jedes $x$ gibt es ein $\xi$ zwischen $a$ und $x$ mit
>>>$$R_{m+1}(x) = \frac{f^{(m+1)}(\xi)}{(m+1)!}(x-a)^{m+1}$$
>>>
>>>- Darstellung von Cauchy
>>>$$R_{m+1}(x) = \frac{1}{m!}\int_a^x (x-t)^m f^{(m+1)}(t) \mathop{\mathrm{d}t}$$
>>>
>>>>[!PROOF]- Beweis
>
>>[!QUOTE] Erklärung zur Definition
>>Die Taylorpolynome von $f$ um den Entwicklungspunkt $a$ erlauben einem den Wert $f(a)$ näherungsweise zu bestimmen. Diese Approximation kann auch für die Bestimmung von $f(a\pm\varepsilon)$ gut sein, wenn $\varepsilon$ klein ist.

>[!DEFINITION] Definition: Taylorreihe
>Sei $f:I\subseteq\mathbb{R}\to\mathbb{R}$ eine beliebig oft [stetig differenzierbare](../Höhere%20Ableitungen.md) [Funktion](../../Funktionen/Funktion.md).
>
>Die **Taylorreihe** von $f$ in $a\in I$ ist die [Reihe](../../Reihen/Reihe.md)
>$$T_{f,a}(x) \overset{\text{def}}{=} \sum_{k=0}^\infty \frac{f^{(k)}(a)}{k!} (x-a)^k$$
>
>>[!IMPORTANT] Satz: Gleichheit von Funktion und Taylorreihe
>>Es gilt
>>$$f(x) = T_{f,a}(x) \iff \lim_{m\to\infty}R_{m+1} = 0$$
>>>[!PROOF]- Beweis