>[!THEOREM] Satz: Polynominterpolation
>Füe alle $n$ verschiedenen Punkte $(x_1, y_1),\cdots, (x_n,y_n)\in\mathbb{R}^2$ gibt es genau ein [Polynom](Polynom.md) $P$, das alle $n$ Punkte durchläuft, also 
>$$P(x_i)=y_i \qquad \forall i \in \{1,\cdots,n\}$$
>Der [Grad](Polynom.md) von $P$ ist höchstens $n-1$.
>$$\deg(P) \le n-1$$
>>[!PROOF]- Beweis

>[!ALGORITHM] Algorithmus: Polynominterpolation (Lagrange'sche Formel)
>Das [Polynom](Polynom.md) $P$, das die Punkte $(x_1, y_1),\cdots, (x_n,y_n)$ durchläuft, ist durch die folgende Formel gegeben.
>$$P(x) = \sum_{i=1}^n \left(y_i \prod_{\begin{matrix}j=1\\ j\ne i\end{matrix}}^n \frac{x-x_j}{x_i-x_j}\right)$$

>[!ALGORITHM] Algorithmus: Polynominterpolation (nach Newton)
>Um das [Polynom](Polynom.md) $P$, das die Punkte $(x_1, y_1),\cdots, (x_n,y_n)$ durchläuft, zu bestimmen:
>1. Mache den Ansatz
>$$P(x) = \lambda_0 + \lambda_1(x-x_1) + \lambda_2 (x-x_1)(x-x_2) + \cdots + \lambda_{n}(x-x_1)(x-x_2)\cdots(x-x_{n-1})$$
>
>2. Bestimme $\lambda_0,\cdots,\lambda_{n}$ in genau dieser Reihenfolge durch Auswerten von $P$ an den Stellen $x_1,\cdots,x_n$, wobei $P(x_i)=y_i$ zu setzen ist.
>3. Ersetze die resultierenden Werte für $\lambda_0,\cdots,\lambda_n$ im Ansatz aus Schritt (1) und multipliziere die Klammern aus, um $P$ zu erhalten.
>
>>[!EXAMPLE]- Beispiel
>>Wir wollen das Interpolarionspolynom $P$ bestimmen, das die Punkte $(1,2),(2,3),(3,6)$ durchläuft.
>>1. Wir machen den Ansatz
>>$$P(x) = \lambda_0 + \lambda_1 (x-1) + \lambda_2 (x-1)(x-2)$$
>>2. Wir bestimmen $\lambda_0,\cdots,\lambda_{n}$:
>>$$2=f(1)=\lambda_0\implies \lambda_0 = 2$$
>>$$3=f(2)=\lambda_0 + \lambda_1 (2-1) = 2 +\lambda_1 \implies \lambda_1 = 1$$
>>$$6=f(3)=\lambda_0 +\lambda_1 (3-1) +\lambda_2(3-1)(3-2)=2+2+2\lambda_2\implies \lambda_2 = 1$$
>>3. Ersetze in $P$
>>$$P(x) = 2 + (x-1) + (x-1)(x-2)= 2 + x - 1 + x^2 -2x -x + 2 = x^2 -2x + 3$$