## Zkouška reveal.js
---
#### Zkouška obrázku

![Obrázek větrných elektráren v zapadajícím slunci](slides-img/1.jpg)
---
#### Zkouška kódu a highlight.js

```cs [1-16|3,2,16|4,5,14,15|6-13|1-16]
//Vykreslování "čtverců" ze znaku * v C#
for (int i = 1; i <= delka; i++)
{
	for (int j = 1; j <= delka; j++)
	{
		if (i == 1 || i == delka || j == 1 || j == delka)
		{
			Console.Write('*');
		}
		else
		{
			Console.Write(' ');
		}
	}
	Console.Write("\n");
}
```
---
#### Zkouška KaTeX

`$$ x_1, x_2 = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$`

`$$ a^2 = b^2 + c^2 - 2bc \cdot \cos \alpha $$`

`$$ \cos (\varphi) = \frac{\vec{u} \cdot \vec{v}}{|\vec{u}| \cdot |\vec{v}|} $$`
---
## Konec
