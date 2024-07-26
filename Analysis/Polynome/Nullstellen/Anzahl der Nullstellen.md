> [!IMPORTANT] Satz: Anzahl der Nullstellen
> Jedes [Polynom](../Polynom.md) $A(x)$ von Grad $n \ge 1$ hat höchstens $n$ verschiedene [Nullstelle](Nullstelle.md).
> > [!CHECK]- Beweis
> > Angenommen, $A(x)$ hätte $n+1$ verschiedene Nullstellen $p_1,\cdots,p_n,p_{n+1}$. Dann lässt sich $A(x)$ folgendermaßen darstellen.
> > $$A(x) = (x-p_1)A_1(x)$$
> > Die Zahl $p_2$ ist auch eine Nullstelle von $A(x)$ und daher gilt
> > $$A(p_2) = (p_2-p_1)A_1(p_2) = 0$$
> > Da die Nullstellen verschieden sind, ist $p_2 \ne p_1$. Also muss $A_1(p_2)$ Null sein. Das heißt, $p_2$ ist eine Nullstelle von $A_1(x)$. Deswegen können wir auch einen Linearfaktor von $A_1(x)$ abspalten:
> > $$A(x) = (x-p_1)(x-p_2)A_2(x)$$
> > Die Zahl $p_3$ ist eine Nullstelle von $A(x)$, also gilt $A(p_3) = (p_3-p_1)(p_3-p_2)A_2(p_3) = 0$, woraus folgt, dass $p_3$ eine Nullstelle von $A_2(x)$ ist und man noch einen Linearfaktor abspalten kann:
> > $$A(x) = (x-p_1)(x-p_2)(x-p_3)A_3(x)$$
> > Dieser Vorgang geht mit allen anderen Nullstellen von $A(x)$ weiter.
> > $$A(x) = (x-p_1)(x-p_2)\cdots (x-p_n)(x-p_{n+1})A_{n+1}(x)$$
> > Allerdings ist $A(x)$ ein Polynom von Grad $n$ und die rechte Seite ist ein Polynom von Grad mindestens $n+1$, was ein Widerspruch ist.