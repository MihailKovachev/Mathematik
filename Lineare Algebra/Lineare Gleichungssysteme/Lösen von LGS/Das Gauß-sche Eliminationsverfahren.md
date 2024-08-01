> [!ALGORITHM] Algorithmus: Das Gauß-sche Eliminationsverfahren
> Das Gauß-sche Eliminationsverfahren ist ein Verfahren, anhand dessen wir die Lösungsmenge eines LGS erhalten können:
> 1. Notiere die erweiterte Koeffizientenmatrix $(A\mid\vec{b})$.
> 2. Bringe die erweiterte Koeffizientenmatrix $(A\mid\vec{b})$ mit elementaren Zeilenumformungen auf [reduzierte Zeilenstufenform](../../Matrizen/Zeilenstufenform/Zeilenstufenform.md).
> 	- Mach den Zeilenführer der ersten Zeile zu 1, indem du diese Zeile mit korrekt gewählten $\lambda \ne 0$ multiplizierst. Benutze diesen Zeilenführer, um nur Nullen darunter zu erzeugen, indem du den rightigen Fachen dieses Zeilenführers von den Zeilen darunter substrahierst. Nun wiederhole diesen Vorgang mit dem Rest der Zeilen, einee nach der anderen.
> 	- Finde den meistrechten Zeilenführer, der gleich 1 ist, und benutze ihn um die Einträge oben ihn zu eliminieren. Wiederhole diesen Vorgang mit der linken Spalte usw.
> 3. Lese die Lösungsmenge $L$ ab.
> 	- Falls eine Zeile der Form $\begin{bmatrix}0 & \cdots & 0 \mid \ast\end{bmatrix}$, wo $\ast \ne 0$, erscheint, ist das System nicht lösbar, also $L = \varnothing$;
> 	- Falls alle Einträge auf der Diagonale von $A$ gleich 1 sind, während alle andere Einträge Null sind, hat das System eine einzige Lösung, die sich direkt ablesen lässt. Der letzte Eintrag der $i$-te Zeile ist der Wert der Unbekannten $x_i$;
> 	- Falls eine oder mehrere Nullzeilen erscheinen, gibt es unendlich viele Lösungen, die aber spezifische Bedingungen erfüllen müssen. In diesem Fall, notiert man die Lösungsmenge $L$ anhand *frei wählbarer Parameter*. Wenn die $j$-te Spalte keinen Zeilenführer enthält, wird die Unbekannte $x_j$ durch solch einen Parameter repräsentiert.
> 
> > [!EXAMPLE]- Beispiel: Keine Lösung
> > Betrachten wir das foglende LGS:
> > $$\left|\begin{align}x + 2y + 3z &= 4 \\ 2x + 4y + 6z &= 10\end{align}\right.$$
> > Wir notieren zunächst die erweiterte Koeffizientenmatrix.
> > $$\left[\begin{array}{ccc|c}1 & 2  & 3 & 4 \\ 2 & 4 & 6 & 10 \end{array}\right]$$
> > Nun bringen wir sie in Zeilenstufenform.
> > $$\left[\begin{array}{ccc|c}1 & 2  & 3 & 4 \\ 2 & 4 & 6 & 10 \end{array}\right] \underset{R_2 \leftarrow R_2 - 2R_1}{\approx} \left[\begin{array}{ccc|c}1 & 2  & 3 & 4 \\ 0 & 0 & 0 & 2 \end{array}\right]$$
> > Da wir eine Zeile der Form $\begin{bmatrix}0 & \cdots & 0 \mid \ast\end{bmatrix}$ erhalten haben, hat das System keine Lösung. Dies können wir mit dem [Lösbarkeitskriterium](Lösbarkeit.md) bestätigen. Betrachten wir die Koeffizientenmatrix
> > $$A = \begin{bmatrix}1 & 2  & 3 \\ 0 & 0 & 0\end{bmatrix}$$
> > Die hat zwei Zeilen, eine von denen eine Nullzeile ist. Dann gilt $\operatorname{rank}(A) = 2 - 1 = 1$. Wir schauen uns nun die erweiterte Koeffizientenmatrix
> > $$(A\mid\vec{b}) = \left[\begin{array}{ccc|c}1 & 2  & 3 & 4 \\ 0 & 0 & 0 & 2 \end{array}\right]$$
> > Die hat auch zwei Zeilen, aber sie enthält keine Nullzeilen, also $\operatorname{rank}(A\mid\vec{b}) = 2$. Da $\operatorname{rank}(A) \ne \operatorname{rank}(A\mid\vec{b})$, ist das System nicht lösbar.
> 
> > [!EXAMPLE]- Beispiel: Eindeutige Lösung
> > Betrachten wir das foglende LGS:
> > $$\left|\begin{align}x + 2y + 3z &= 14 \\ 2x + 5y + 6z &= 30 \\ -x + 2y +3z &= 12\end{align}\right.$$
> > Wir notieren nun die erweiterte Koeffizientenmatrix.
> > $$\left[\begin{array}{ccc|c}1 & 2  & 3 & 14 \\ 2 & 5 & 6 & 30 \\ -1 & 2 & 3 & 12\end{array}\right]$$
> > Da wir schon einen Zeilenführer gleich 1 in der ersten Zeile haben, können wir ihn benutzen um die Einträge darunter zu eliminieren.
> > $$\left[\begin{array}{ccc|c}1 & 2  & 3 & 14 \\ 2 & 5 & 6 & 30 \\ -1 & 2 & 3 & 12\end{array}\right] \underset{R_2 \leftarrow R_2 - 2R_1}{\approx} \left[\begin{array}{ccc|c}1 & 2  & 3 & 14 \\ 0 & 1 & 0 & 2 \\ -1 & 2 & 3 & 12\end{array}\right] \underset{R_3 \leftarrow R_3 + R_1}{\approx} \left[\begin{array}{ccc|c}1 & 2  & 3 & 14 \\ 0 & 1 & 0 & 2 \\ 0 & 4 & 6 & 26\end{array}\right]$$
> > Diesen Vorgang machen wir nun mit dem Zeilenführer der zweiten Zeile wieder.
> > $$\left[\begin{array}{ccc|c}1 & 2  & 3 & 14 \\ 0 & 1 & 0 & 2 \\ 0 & 4 & 6 & 26\end{array}\right] \underset{R_3 \leftarrow R_3 - 4R_2}{\approx} \left[\begin{array}{ccc|c}1 & 2  & 3 & 14 \\ 0 & 1 & 0 & 2 \\ 0 & 0 & 6 & 18\end{array}\right]$$
> > Die Matrizen $A$ und $(A \mid \vec{b})$ sind nun in [Zeilenstufenform](../../Matrizen/Zeilenstufenform/Zeilenstufenform.md) und wir können die Anzahl der Lösungen anhand des [Lösbarkeitskriteriums](Lösbarkeit.md) untersuchen. Die Koeffizientenmatrix 
> > $$A = \begin{bmatrix}1 & 2  & 3 \\ 0 & 1 & 0 \\ 0 & 0 & 6 \end{bmatrix}$$
> > hat drei Zeilen, die keine Nullzeilen sind, also $\operatorname{rank}(A) = 3$. Dasselbe gilt für die erweiterte Koeffizientenmatrix
> > $$(A \mid\vec{b}) = \left[\begin{array}{ccc|c}1 & 2  & 3 & 14 \\ 0 & 1 & 0 & 2 \\ 0 & 0 & 6 & 18\end{array}\right]$$
> > Da $\operatorname{rank} (A) = 3 = \operatorname{rank} (A\mid\vec{b})$ gilt, ist das System lösbar. Das LGS verfügt über drei Unbekannte: $x, y, z$. Dann gilt
> > $$\text{Anzahl der frei wählbaren Parameter} = 3 - \operatorname{rank} (A) = 3 - 3 = 0$$
> > Wir haben also *keine* frei wählbaren Parameter, was heißt, dass das System eine eindeutige Lösung hat. Um diese Lösung zu finden, müssen wir die erweiterte Koeffizientenmatrix $(A\mid\vec{b})$ auf [reduzierte Zeilenstufenform](../../Matrizen/Zeilenstufenform/Zeilenstufenform.md) bringen.
> > 
> > Zuerst machen wir so, dass der letzte Zeilenführer gleich 1 ist.
> > $$\left[\begin{array}{ccc|c}1 & 2  & 3 & 14 \\ 0 & 1 & 0 & 2 \\ 0 & 0 & 6 & 18\end{array}\right] \underset{R_3 \leftarrow \frac{1}{6}R_3}{\approx} \left[\begin{array}{ccc|c}1 & 2  & 3 & 14 \\ 0 & 1 & 0 & 2 \\ 0 & 0 & 1 & 3\end{array}\right]$$
> > 
> > Nun machen wir Gebrauch von diesem Zeilenführer, indem wir ihn benutzen, um die Einträge darüber zu eliminieren.
> > $$\left[\begin{array}{ccc|c}1 & 2  & 3 & 14 \\ 0 & 1 & 0 & 2 \\ 0 & 0 & 1 & 3\end{array}\right] \underset{R_1 \leftarrow R_1 - 3R_3}{\approx} \left[\begin{array}{ccc|c}1 & 2  & 0 & 5 \\ 0 & 1 & 0 & 2 \\ 0 & 0 & 1 & 3\end{array}\right]$$
> > Diesen Vorgang wiederholen wir mit dem Zeilenführer der Zeile darüber.
> > $$\left[\begin{array}{ccc|c}1 & 2  & 0 & 5 \\ 0 & 1 & 0 & 2 \\ 0 & 0 & 1 & 3\end{array}\right] \underset{R_1 \leftarrow R_1 - 2R_2}{\approx} \left[\begin{array}{ccc|c}1 & 0  & 0 & 1 \\ 0 & 1 & 0 & 2 \\ 0 & 0 & 1 & 3\end{array}\right]$$
> > Die Matrix ist jetzt in erweiterter Zeilenstufenform und die Lösung lässt sich direkt ablesen. Die $i$-te Zeile entspricht der $i$-ten Variable.
> > $$\begin{align}x &= 1 \\ y &= 2 \\ z &= 3\end{align} \implies L = \{(1,2,3)\}$$
>
> > [!EXAMPLE]- Beispiel: Unendlich viele Lösungen
> > Betrachten wir das folgende LGS.
> > $$\left|\begin{align}x_3 + 3x_4 + 3x_5 &= 2 \\ x_1 + 2x_2 + x_3 + 4x_4 + 3x_5 &= 3 \\ x_1 + 2x_2 + 2x_3 + 7x_4 + 6x_5 &= 5 \\ 2x_1 + 4x_2 + x_3 + 5x_4 + 3x_5 &= 4\end{align}\right.$$
> > Wir notieren zuerst die erweiterte Koeffizientenmatrix.
> > $$\left[\begin{array}{ccccc|c}0 & 0  & 1 & 3 & 3 & 2 \\ 1 & 2 & 1 & 4 & 3 & 3 \\ 1 & 2 & 2 & 7 & 6 & 5 \\ 2 & 4 & 1 & 5  & 3 & 4\end{array}\right]$$
> > Diese müssen wir auf Zeilenstufenform bringen.
> > $$\left[\begin{array}{ccccc|c}0 & 0  & 1 & 3 & 3 & 2 \\ 1 & 2 & 1 & 4 & 3 & 3 \\ 1 & 2 & 2 & 7 & 6 & 5 \\ 2 & 4 & 1 & 5  & 3 & 4\end{array}\right] \underset{R_1 \leftrightarrow R_2}{\approx} \left[\begin{array}{ccccc|c} 1 & 2 & 1 & 4 & 3 & 3 \\ 0 & 0  & 1 & 3 & 3 & 2 \\ 1 & 2 & 2 & 7 & 6 & 5 \\ 2 & 4 & 1 & 5  & 3 & 4\end{array}\right] \underset{R_3 \leftarrow R_3 - R_1}{\approx} \left[\begin{array}{ccccc|c} 1 & 2 & 1 & 4 & 3 & 3 \\ 0 & 0  & 1 & 3 & 3 & 2 \\ 0 & 0 & 1 & 3 & 3 & 2 \\ 2 & 4 & 1 & 5  & 3 & 4\end{array}\right]$$
> > $$\left[\begin{array}{ccccc|c} 1 & 2 & 1 & 4 & 3 & 3 \\ 0 & 0  & 1 & 3 & 3 & 2 \\ 0 & 0 & 1 & 3 & 3 & 2 \\ 2 & 4 & 1 & 5  & 3 & 4\end{array}\right] \underset{R_4 \leftarrow R_4 - 2R_1}{\approx} \left[\begin{array}{ccccc|c} 1 & 2 & 1 & 4 & 3 & 3 \\ 0 & 0  & 1 & 3 & 3 & 2 \\ 0 & 0 & 1 & 3 & 3 & 2 \\ 0 & 0 & -1 & -3  & -3 & -2\end{array}\right]$$
> > $$\left[\begin{array}{ccccc|c} 1 & 2 & 1 & 4 & 3 & 3 \\ 0 & 0  & 1 & 3 & 3 & 2 \\ 0 & 0 & 1 & 3 & 3 & 2 \\ 0 & 0 & -1 & -3  & -3 & -2\end{array}\right] \underset{R_3 \leftarrow R_3 - R_2}{\approx} \left[\begin{array}{ccccc|c} 1 & 2 & 1 & 4 & 3 & 3 \\ 0 & 0  & 1 & 3 & 3 & 2 \\ 0 & 0 & 0 & 0 & 0 & 0 \\ 0 & 0 & -1 & -3  & -3 & -2\end{array}\right] \underset{R_4 \leftarrow R_4 + R_2}{\approx} \left[\begin{array}{ccccc|c} 1 & 2 & 1 & 4 & 3 & 3 \\ 0 & 0  & 1 & 3 & 3 & 2 \\ 0 & 0 & 0 & 0 & 0 & 0 \\ 0 & 0 & 0 & 0  & 0 & 0\end{array}\right]$$
> > Betrachten wir jetzt die Koeffizientenmatrix
> > $$A = \begin{bmatrix}1 & 2 & 1 & 4 & 3 \\ 0 & 0  & 1 & 3 & 3 \\ 0 & 0 & 0 & 0 & 0 \\ 0 & 0 & 0 & 0  & 0\end{bmatrix}$$
> > Sie hat vier Zeilen und zwei davon sind Nullzeilen. Das heißt $\operatorname{rank}(A) = 4 - 2 = 2$. Nun betrachten wir die erweiterte Koeffizientenmatrix.
> > $$(A \mid\vec{b}) = \left[\begin{array}{ccccc|c} 1 & 2 & 1 & 4 & 3 & 3 \\ 0 & 0  & 1 & 3 & 3 & 2 \\ 0 & 0 & 0 & 0 & 0 & 0 \\ 0 & 0 & 0 & 0  & 0 & 0\end{array}\right]$$
> > Auch sie hat vier Zeilen, zwei von denen Nullzeilen sind. Das heißt $\operatorname{rank}(A\mid\vec{b}) = 4 -2 =2$. Da $\operatorname{rank}(A) = \operatorname{rank}(A\mid\vec{b})$, ist das System lösbar. Das LGS hat fünf Unbekannte, also
> > $$\text{Anzahl der frei wählbaren Parameter} = 5 - \operatorname{rank} (A) = 5 - 2 = 3$$
> > Wir haben also drei Variablen, die willkürlich gewählt werden können. Wir weisen diesen Variablen die sogennanten *Parameter* zu und stellen die anderen zwei Variablen anhand dieser Parameter dar. Beispielsweise können wir 
> > $$\begin{align}x_2 &= \lambda \\ x_4 &= \mu \\ x_5 &= \nu \end{align} \qquad \lambda, \mu, \nu \in \mathbb{R}$$
> > wählen. Aus der zweiten Zeile erhalten wir dann eine Bedingung für $x_3$, nämlich
> > $$x_3 = 2 - 3x_4 -3x_5 = 2-3\mu-3\nu$$
> > Aus der ersten Zeile erhalten wir ähnlicherweise eine Bedingung für $x_1$:
> > $$x_1 = 3 - 2x_2 - x_3-4x_4 -3x_5 = 3-2\lambda-2+3\mu+3\nu-4\mu-3\nu = 1-2\lambda-\mu$$
> > Die Lösungensmenge ist dann
> > $$L = \{(1-2\lambda-\mu, \lambda, 2-3\mu-3\nu, \mu,\nu) \mid \lambda,\mu,\nu \in \mathbb{R}\} = \left\{\begin{bmatrix}1 \\ 0 \\ 2 \\ 0 \\ 0\end{bmatrix} + \lambda \begin{bmatrix}-2 \\ 1 \\ 0 \\ 0 \\ 0\end{bmatrix} + \mu \begin{bmatrix}-1 \\ 0 \\ -3 \\ 1 \\ 0\end{bmatrix} + \nu \begin{bmatrix}0 \\ 0 \\ -3 \\ 0 \\ 1\end{bmatrix} \mid \lambda,\mu,\nu \in \mathbb{R}\right\}$$
> > Hätten wir andere Variablen als freie Parameter gewählt, würde die Lösungsmenge eine andere Form annehmen, die aber equivalent zu dieser hier wäre.