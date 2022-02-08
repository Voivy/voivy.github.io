# Vektorová algebra
## Orientovaná úsečka:
- = úsečka, u níž rozlišujeme počáteční a koncový bod; znázorňujeme ji šipkou směřující ke koncovému bodu

*Př. 1: Spíše než příklad je to otázka. Liší se velikost orientované úsečky od běžné úsečky?*

## Vektor:
- = množina všech orientovaných úseček, které mají stejnou velikost a směr; v širším obzoru je vektorem vše, co splňuje vlastnosti vektoru
- vektory značíme obvykle `$\vec{u}$`
- vektor se skládá z jednotlivých složek, dvourozměrné nebo trojrozměrné vektory můžeme zapsat s jejich pomocí jako:  `$$\vec{u} = (u_1; u_2) \qquad nebo \qquad \vec{u} = (u_1; u_2; u_3)$$`
- pro složky vektoru $\vec{u}$ zadaného body $A$ a $B$ platí, že jednotlivé složky vektoru získáme odečtením jednotlivých souřadnic těchto dvou bodů; důležité je, že odčítáme vždy souřadnice počátečního bodu od souřadnic koncového bodu:`$$u_1 = b_1 - a_1 \qquad \qquad u_2 = b_2 - a_2 \qquad \qquad (u_3 = b_3 - a_3)$$`
- třetí ze souřadnic je volitelná - záleží, jestli pracujeme ve dvou nebo ve třech rozměrech

*Př. 2: Určete složky vektoru zadaného počátečním bodem `$K[1;5;3]$` a koncovým bodem `$L[7;9;2]$`.*

## Velikost vektoru:
- velikost vektoru značíme `$|\vec{u}|$`
- získáme ji pomocí Pythagorovy věty ze složek onoho vektoru:
`$$|\vec{u}| = \sqrt{ {u_1}^2 + {u_2}^2} \qquad nebo \qquad |\vec{u}| = \sqrt{ {u_1}^2 + {u_2}^2 + {u_3}^2}$$`
- **nulový vektor** = vektor s nulovou velikostí (nemá směr ani orientaci), označujeme jej `$\vec{o}$`
- **jednotkový vektor** = vektor jehož velikost je rovna 1

*Př. 3: Je dán vektor `$\vec{u} = (2;3;6)$`. Určete velikost tohoto vektoru.*

## Součet vektorů:
- probíhá poměrně přímočaře, sčítáme jednotlivé složky vektoru
- má typické vlastnosti, které bychom od součtu čekali (komutativní, asociativní, ...)
- pro součet vektorů `$u$` a `$v$` platí:`$$\vec{u} + \vec{v} = (u_1 + v_1; u_2 + v_2) \qquad nebo \qquad \vec{u} + \vec{v} = (u_1 + v_1; u_2 + v_2; u_3 + v_3)$$`
- kromě výpočtu lze vektory sčítat také graficky (jeden z vektorů přesuneme tak, aby jeho počáteční bod ležel na koncovém bodu druhého z vektorů; výsledkem je pak vektor směřující z úplného počátku do koncového bodu přesunutého vektoru)
- **opačný vektor** = vektor, který pokud sečteme s vektorem původním, dostaneme `$\vec{o}$`; opačný vektor značíme znaménkem minus  - např. `$-\vec{u}$`

*Př. 4: Sečtěte početně i graficky vektory `$\vec{u} = (2;3)$` a `$\vec{v} = (6;4)$`. Výsledky porovnejte.*

## Rozdíl vektorů:
- takřka totožný se součtem, místo sčítání pouze odčítáme
- pro součet vektorů `$u$` a `$v$` platí:`$$\vec{u} - \vec{v} = (u_1 - v_1; u_2 - v_2) \qquad nebo \qquad \vec{u} - \vec{v} = (u_1 - v_1; u_2 - v_2; u_3 - v_3)$$`
- odčítat lze také graficky - buď k odčítanému vektoru vytvoříme vektor opačný a poté graficky sčítáme, nebo oba vektory zakreslíme se stejným počátečním bodem a výsledným vektorem je pak spojnice obou koncových vektorů (směřována od vektoru odčítaného)

*Př. 5: Odečtěte početně i graficky (oběma způsoby) vektor `$\vec{u} = (2;3)$` od vektoru `$\vec{v} = (6;4)$`. Výsledky porovnejte.*

## Násobení vektoru reálným číslem:
- pokud násobím vektor reálným číslem, násobím v podstatě každou z jeho složek tímto číslem; platí tedy:`$$k \cdot \vec{u} = (k \cdot u_1; k \cdot u_2) \qquad nebo \qquad k \cdot \vec{u} = (k \cdot u_1; k \cdot u_2; k \cdot u_3)$$`
- pokud je `$k$` záporné, dochází u vektoru k změně směru na směr opačný oproti původnímu
- násobení vektorů má vlastnosti typické pro násobení (asociativní, distributivní, ...)

*Př. 6: Kolikrát se zvětší velikost vektoru `$\vec{u} = (-6;8)$`, pokud jej vynásobíme číslem minus tři? Jak se změní jeho směr?*

## Lineární kombinace vektorů:
- vektor lze také vyjádřit jako tzv. lineární kombinaci dvou jiných vektorů (tyto vektory však nesmí být rovnoběžné):`$$\vec{x} = r \cdot \vec{u} + s \cdot \vec{v} \qquad nebo \qquad \vec{x} = r \cdot \vec{u} + s \cdot \vec{v} + t \cdot \vec{w}$$`
- význam tohoto postupu je však přesně opačný - mohu mít dva oblíbené vektory, pomocí nichž pak vyjádřím jakýkoliv jiný vektor
- toto funguje i v prostoru, musím však mít tři oblíbené vektory

*Př. 7. Mám vektory `$\vec{u} = (2;3)$` a `$\vec{v} = (-1;4)$`. Jak bych pomocí nich vyjádřil vektor `$\vec{w} = (10;4)$`?*

## Skalární součin:
- vektory můžeme vzájemně násobit dvěma způsoby, tím prvním a jednodušším je skalární součin
- značíme ho tečkou jako běžné násobení; jeho výsledkem je **reálné číslo**
- vypočítáme jej:`$$\vec{u} \cdot \vec{v} = u_1 \cdot v_1 + u_2 \cdot v_2 \qquad nebo \qquad \vec{u} \cdot \vec{v} = u_1 \cdot v_1 + u_2 \cdot v_2 + u_3 \cdot v_3$$`
- pokud jsou vektory na sebe kolmé, je skalární součin roven nule (v rovině snadno určíme k vektoru vektor kolmý, stačí nám vyměnit jeho složky a jednu z nich vynásobit `$-1$`)

*Př. 8: Určete skalární součin vektoru `$\vec{u} = (4;3)$` a vektoru kolmého k vektoru `$\vec{v} = (-1;5)$`.*

## Vektorový součin:
- druhý způsob násobení vektorů, je použitelný pouze v prostoru
- značíme ho křížkem; jeho výsledkem je **vektor** kolmý k oběma násobeným vektorům o velikosti odpovídající obsahu plochy rovnoběžníku vytyčeného těmito dvěmi vektory
- o souřadnicích tohoto výsledného vektoru, označme si jej `$\vec{w}$`, platí:`$$w_1 = u_2 \cdot v_3 - u_3 \cdot v_2 \qquad w_2 = u_3 \cdot v_1 - u_1 \cdot v_3 \qquad w_3 = u_1 \cdot v_2 - u_2 \cdot v_1$$`
- vektorový součin používáme zejména pro naleznutí normálového vektoru k rovině, jež je v analytické geometrii určena parametricky

*Př. 9: Určete vektorový součin vektorů `$\vec{u} = (1;3;-1)$` a  `$\vec{v} = (2;4;5)$`.*

## Odchylka vektorů:
- pokud máme dány dva vektory, můžeme určit jejich odchylku pomocí vztahu: `$$\cos{\varphi} = \frac{\vec{u} \cdot \vec{v} }{|\vec{u}| \cdot |\vec{v}|}$$`
- tento vztah vychází z kosinové věty a platí pro dva i pro tři rozměry (je však nutné použít odpovídající vzorec pro skalární součin i pro velikost vektoru)
- velikost odchylky náleží do intervalu `$\langle 0°;180° \rangle$`
- **rovnoběžné vektory** = jeden z vektorů je násobkem druhého (jejich odchylka je tedy `$0°$` nebo `$180°$`)

*Př. 10: Určete odchylku vektorů `$\vec{u} = (4;3)$` a `$\vec{v} = (7;-1)$`.*

## Obsah trojúhelníku:
- pokud máme vypočítat obsah trojúhelníku, jehož dvě strany jsou tvořeny vektory, můžeme použít vztah:`$$S = \frac{1}{2} \cdot |\vec{u}| \cdot |\vec{v}| \cdot \sin{\varphi}$$`
- jedná se vlastně o analogii typického vztahu z trigonometrie

*Př. 11: Jsou dány body `$A[1;2]$`, `$B[4;-3]$` a `$C[9;0]$`, které vytvářejí trojúhelník. Vypočítejte obsah tohoto trojúhelníku.*
