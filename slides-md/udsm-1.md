# Relace a zobrazení
---
## 1. dějství

<hr>

Anna Schovajsová
---
### Kartézský součin dvou množin

<hr>

`$A\times B=\left\{\left(a;b\right)\middle| a\in A\ \land b\in B\right\}$`
---
### Kartézský součin tří množin

<hr>

`$A\times B\times C=\left\{\left(a;b;c\right)\middle| a\in A\ \land b\in B\land c\in C\right\}$`
---
Kartézský součin **není komutativní**.

`$A\times B\neq B\times A$`
---
<hr>

### Kartézský součin konečných množin

<hr>
---
`$A=\left\{1;2\right\} \quad B=\left\{3;4\right\}$`

<hr>

`$A \times B\ =\ \left\{\left(1;3\right);\left(1;4\right);\left(2;3\right);\left(2;4\right)\right\}$`

---
![kartézský součin konečných množin](slides-img/rel1-0.png)
---
<hr>

### Kartézský součin nekonečných množin

<hr>
---
`$A=\left\{1;2;3\right\} \quad B=\langle 1;3 \rangle$`

<hr>

![kartézský součin konečných množin](slides-img/rel1-1.png)
---
`$A=\langle 1;3 \rangle \quad B=\langle 1;3 \rangle$`

<hr>

![kartézský součin konečných množin](slides-img/rel1-2.png)
---
### Binární relace

<hr>
= vztah mezi dvěma množinami, podmnožina kartézského součinu $ \rho \subseteq A \times B $
---

**Zápis:**

<hr>

`$(a; b) \in \rho$`

`$a \rho b$`
---
**Příklad relací z praxe:**

<hr>

`$A\text{ ... žáci ve třídě}$`

`$B = \left\{1;2;3;4;5\right\}$`

<hr>

`$a \rho b \iff \text{žák a dostal známku b}$`
---
**Další příklad:**

<hr>

`$A = \mathbb{R}$`

`$B = (0; +\infty)$`

<hr>

`$a \rho b \iff y = 2^x$`

---
### Speciální druh relace –&#160;relace&#160;na&#160;množině

<hr>

`$\rho \subseteq A \times A$`

`$A\times A=A^2$`

---
**Příklad z praxe:**

<hr>

`$A = \{ Brno, Ostrava, Praha, Zlín, Olomouc\}$`

<hr>

`$a \rho b \iff \text{pokud vede cesta z města a do města b}$`
---
**Matematický příklad:**

<hr>

`$A = \mathbb{N}$`

<hr>

`$a \rho b \iff a \geq b$`
---
## 2. dějství

<hr>

Vojtěch Vybíralík
---
![ukázka relace na rovnoběžnosti přímek](slides-img/rel2-0.png)
---
Relace `$R$`: `$x$` je rovnoběžné s `$y$`.
---
![ukázka relace na rovnoběžnosti přímek](slides-img/rel2-0.png)
---
![zakreslení relace do kartézského grafu](slides-img/rel2-1.png)
---
![zakreslení relace do kartézského grafu - reflexivní](slides-img/rel2-2.png)
---
Relaci `$R$` v množině  `$M$` nazýváme **reflexivní** právě tehdy, když platí:

`$$(\forall x \in M)((x,x) \in R)$$`
---
![ukázka relace na rovnoběžnosti přímek](slides-img/rel2-0.png)
---
![zakreslení relace do kartézského grafu - reflexivní](slides-img/rel2-2.png)
---
Relaci `$R$` v množině  `$M$` nazýváme **antireflexivní** právě tehdy, když platí:

`$$(\forall x \in M)((x,x) \notin R)$$`
---
![zakreslení relace do kartézského grafu](slides-img/rel2-1.png)
---
![zakreslení relace do kartézského grafu - symetrická](slides-img/rel2-3.png)
---
Relaci `$R$` v množině  `$M$` nazýváme **symetrická** právě tehdy, když platí:

`$$(\forall x,y \in M)((x,y) \in R \implies (y,x) \in R)$$`
---
![ukázka relace na rovnoběžnosti přímek](slides-img/rel2-0.png)
---
![zakreslení relace do kartézského grafu - symetrická](slides-img/rel2-3.png)
---
Relaci `$R$` v množině  `$M$` nazýváme **antisymetrická** právě tehdy, když platí:

`$$(\forall x,y \in M)((x,y) \in R \land (y,x) \in R \implies x = y)$$`
---
![ukázka relace na rovnoběžnosti přímek](slides-img/rel2-0.png)
---
Relaci `$R$` v množině  `$M$` nazýváme **tranzitivní** právě tehdy, když platí:

`$$(\forall x,y,z \in M)(((x,y) \in R \land (y,z) \in R) \implies (x,z) \in R)$$`
---
![ukázka relace na rovnoběžnosti přímek](slides-img/rel2-0.png)
---
Relaci `$R$` v množině  `$M$` nazýváme **souvislou/konektivní** právě tehdy, když platí:

`$$(\forall x,y \in M)((x,y) \in R \lor (y,x) \in R)$$`
---
![zakreslení relace do kartézského grafu](slides-img/rel2-1.png)
---
**Příklad 1:**

<hr>

*Charakterizujte uzlový graf reflexivní relace, symetrické relace a tranzitivní relace.*
---
**Příklad 2:**

<hr>

*Rozhodněte o relaci "býti větší" v množině reálných čísel, zda je reflexivní, symetrická, tranzitivní a souvislá.*
---
## 3. dějství
<hr>
Arnošt Bekárek
---
### Uspořádání

<hr>

Kvaziuspořádaná množina `$(M, ≤)$` taková, že relace „$≤$“ je antisymetrická, se nazývá **uspořádaná** a relace „$≤$“ se v tomto případě nazývá **uspořádání na M**.
---
### Relace ekvivalence

<hr>

**Relací ekvivalence** (stručně **ekvivalencí**) na množině $M$ rozumíme každou binární relaci na $M$, která je reflexivní, symetrická a tranzitivní.
---
### Rozklad množiny

<hr>

1. `$\bigcup_{i \in I} M_i = M$`
2. Jestliže `$i \neq j$`, pak `$M_i \cap M_j = \emptyset$`
---
**Příklad:**

<hr>

$A = P(\{1,2,3\}) \quad \quad aRb \iff |a| = |b|$

<hr>

a) Určete, zda se jedná o relaci ekvivalence.

b) Proveďte rozklad množiny.
---
## 4. dějství
<hr>
Jan Klemeš
---
### Relace mezi množinami (=&#160;korespondence)

<hr>

**definiční obor f:**

`$Dom \; f = \{ x \in A, \exists y \in B \; tak, že \; (x,y) \in f\}$`

**obor hodnot f:**

`$Im \; f = \{ y \in B, \exists x \in A \; tak, že \; (x,y) \in f\}$`
---
### Inverzní relace

<hr>

Je-li `$R \subseteq A \times B$` binární relací mezi množinami `$A$` a `$B$`, pak **inverzní relací** k relaci `$R$` rozumíme relaci `$R^{-1} \subseteq B \times A$` takovou, že `$\forall a \in A, b \in B ; (b, a) \in R^{-1} \iff (a, b) \in R$`.
---
**Příklad:**

<hr>

`$A = \{1, 2\} \quad B = \{2, 4, 6\}$`

<hr>

`$$R = \{(1,2);(1,4);(1,6);(2,2);(2,4);(2,6)\}$$`

`$$R^{-1} = \{(2,1);(2,2);(4,1);(4,2);(6,1);(6,2)\}$$` <!-- .element: class="fragment" data-fragment-index="2" -->
---
### Doplňková relace

<hr>

`$$R' = A \times B \setminus R$$`
---
**Příklad:**

<hr>

`$A = \{1, 2\} \quad B = \{2, 4, 6\}$`

<hr>

`$$R = \{(2,2);(2,4);(2,6)\}$$`

`$$R' = \{(1,2);(1,4);(1,6)\}$$` <!-- .element: class="fragment" data-fragment-index="2" -->
---
## 5. dějství

<hr>

Radim Křenek
---
### Složení binárních relací

<hr>

Nechť `$R \subseteq A \times B, S \subseteq B \times C$`

`$R \circ S \subseteq A \times C$`

<hr>

`$\forall a \in A, c \in C; (a, c) \in R \circ S$`

`$\iff$`

`$(\exists b \in B, (a, b) \in R \land (b, c) \in S)$`

---
**Příklad:**

<hr>

`$A = \{a, b, c, d\} \quad B = \{α, β, γ\} \quad C = \{1, 2, 3\}$`

`$R \subseteq A \times B \quad S \subseteq B \times C$`

<hr>

`$R = \{(a, β), (b, α), (a, γ), (c, α), (d, β), (b, γ)\}$`

`$S = \{(α, 2), (α, 3), (β, 1), (β, 3), (γ, 1)\}$`

<hr>

`$R \circ S = \{(a, 1), (a, 3), (b, 2), (b, 3), (c, 2), (c, 3), (d, 1), (d, 3), (b, 1) \}$`

---
### Zobrazení

<hr>

`$f: A \to B$`

<hr>

`$\forall a \in A \; \exists b \in B; (a, b) \in f$`

`$\forall a \in A \; b_1, b_2 \in B; [(a, b_1) \in f \land (a, b_2) \in f] \implies b_1 = b_2$`

---
**Příklad:**

<hr>

`$A = \{ a, b, c \} \quad B = \{ 1, 2 \} \quad T: A \to B$`

<hr>
<br>

![zakreslení relace do kartézského grafu](slides-img/rel5-0.png)

---

![zakreslení relace do pseudouzlového grafu](slides-img/rel5-1.png)

---
## 6. dějství

<hr>

Tomáš David
---
### Injektivní (prosté) zobrazení

<hr>

= každý vzor má jiný obraz

`$f: A \to B$`
---
**Definice:**

<hr>

`$(\forall x, y \in A):[(f(x) = f(y) \implies (x = y))]$`

<br>

**Druhý způsob definice:**

<hr>

`$(\forall x, y \in A):[(x \neq y \implies (f(x) \neq f(y))]$`
---
**Příklady:**

<hr>

`$f: \mathbb{N} \to \mathbb{Z}$`

`$f(x) = 2x$`
---
### Surjektivní zobrazení

<hr>

`$f: A \to B$`
---
**Definice:**

<hr>

`$(\forall x \in B)(\exists y \in A)(x = f(y))$`
---
**Příklady:**

<hr>

`$f: \mathbb{Z} \to \mathbb{Z}$`

`$f(x) = x - 2$`
---
### Bijektivní zobrazení

<hr>

= surjektivní zobrazení + injektivní zobrazení

`$f: A \to B$`
---
**Příklady:**

<hr>

`$f: \mathbb{Z} \to \mathbb{Z}$`

`$f(x) = x - 2$`
---
### Identita (=&#160;permutace&#160;konečné&#160;množiny)

<hr>

= zobrazení samo na sebe

`$f: A \to A, f(x) = x$`
---
**Příklady:**

<hr>

`$f: \mathbb{N} \to \mathbb{N}$`

`$f(x) = x$`
---
# Děkujeme za pozornost
