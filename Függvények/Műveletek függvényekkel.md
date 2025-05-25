Legyenek $f$ és $g$ olyan valós-valós függvények, amelyekre $D_f \cap D_g\neq0$. Ekkor $f$ és $g$ összegén, különbségén és szorzatán azokat az $f+g$, $f-g$ és $f*g$ függvényket értjük, amelyek a $D_f \cap D_g$ halmazon vannak értelmezve és amelyekre teljesül, hogy $\forall x \in D_f \cap D_g$ esetén
$$
(f+g)(x) = f(x)+g(x)
$$
$$
(f-g)(x) = f(x)-g(x)
$$
$$
(f*g)(x) = f(x)*g(x)
$$

Legyenek $f$ és $g$ valós-valós függvények, $N = \{x|x\in D_g, g(x)=0\}$ ($g$ zérushelyeinek halmaza) és $(D_f\cap D_g)\setminus N \neq 0$. Ekkor $f$ és $g$ hányadosán azt az $\frac{f}{g}$ függvényt értjük, amely $(D_f\cap D_g)\setminus N$ halmazon van értelmezve és amelyre teljesül, hogy $\forall x (D_f \cap D_g)\setminus N$ esetén
$$
(\frac{f}{g})(x) = \frac{f(x)}{g(x)}
$$

Ha az $f$ és $g$ függvények folytonosak az $x_0$-ban, akkor $f+g$, $f-g$ és $f*g$ is folytonosak az $x_0$-ban.
Ha az $f$ és $g$ függvények folytonosak az $x_0$-ban és $g(x)\neq0$, akkor az $\frac{f}{g}$ függvény is folytonos az $x_0$-ban.

Példa:
- $x \mapsto x^2 +2x+3$ függvény mindenütt folytonos, mert $x \mapsto x$ folytonos, így ennek önmagával való szorzata $x \mapsto x^2$ is folytonos. $x \mapsto 2x$ is folytonos, mert az $x \mapsto x$ és az $x \mapsto 2$ folytonos függvények szorzata. Így $x \mapsto x^2+2x+3$ három folytonos függvény összege, tehát szintén folytonos.
