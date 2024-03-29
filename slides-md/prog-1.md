# Rekurze

---

### 1.

Napište rekurzivní funkci `digitSum`, která vypočítá ciferný součet zadaného přirozeného čísla.

<br>

```cs
digitSum(18)    // -> 9
digitSum(12345) // -> 15
digitSum(9999)  // -> 36
```

--

```cs
int digitSum(int a)
{
  if(a == 0)
  {
    return 0;
  }
  else
  {
    return (a % 10) + digitSum(a / 10);
  }
}
```

--

```cs
int digitSum(int a)
{
    if(a == 0) return 0;

    return (a % 10) + digitSum(a / 10);
}
```

---

*vsuvka o Fibonacciho posloupnosti...*

--

```cs
static int F(int n)
{
    if(n == 1 || n == 0) return n;

    return F(n - 1) + F(n - 2);
}
```

---

### 2.

Funkce `fibonacci` spolu s pomocnou funkcí `fib` je vylepšenou variantou rekurzivní funkce pro výpočet Fibonacciho posloupnosti, kterou znáte z minulé hodiny. V čem je lepší? Popište, jak funguje. Porovnejte rychlost výpočtu této funkce a její běžné, "hloupé" verze. Je funkce `fibonacci` skutečně rekurzivní?

--

```cs
static int fibonacci(int n)
{
   return fib(n, new int[n + 1]);
}

static int fib(int n, int[] pole)
{
   if (n == 1 || n == 0) return n;

   if (pole[n] == 0) pole[n] = fib(n - 1, pole) + fib(n - 2, pole);

   return pole[n];
}
```

---

### 3.

Přirozené číslo je dělitelné devíti právě tehdy, když je jeho ciferný součet dělitelný devíti. Za pomocí této vlastnosti napište rekurzivní funkci `isDivisibleByNine`, která bez použití operátoru `%` zjistí, zda je zadané přirozené číslo dělitelné devíti. Využijte funkce `digitSum` z předchozího příkladu.

<br>

```cs
isDivisibleByNine(9)        // -> True
isDivisibleByNine(27)       // -> True
isDivisibleByNine(12345678) // -> True
isDivisibleByNine(91)       // -> False
```

--

```cs
bool isDivisibleByNine(int a)
{
    if (a == 9) return true;
    if (a < 9) return false;

    return isDivisibleByNine(digitSum(a));
}
```

--

```cs
bool isDivisibleByNine2(int a)
{
    return (a == 9) || (a > 9 && isDivisibleByNine2(digitSum(a)));
}
```

---

### 4.

Přirozené číslo je dělitelné třemi právě tehdy, když je jeho ciferný součet dělitelný třemi. Upravte tedy funkci `isDivisibleByNine` na funkci `isDivisibleByThree`, která bez použití operátoru `%` zjistí, zda je zadané přirozené číslo dělitelné třemi. Jediné, co se změní oproti předchozí funkci, bude ukončovací podmínka (a název).

```cs
isDivisibleByThree(9)        // -> True
isDivisibleByThree(24)       // -> True
isDivisibleByThree(12345)    // -> True
isDivisibleByThree(52)       // -> False
```

--

```cs
bool isDivisibleByThree(int a)
{
    if (a == 9 || a == 6 || a == 3) return true;
    if (a < 9) return false;

    return isDivisibleByThree(digitSum(a));
}
```

---

### 5.

Toto je *Pascalův trojúhelník*:
`$$1$$$$1 \qquad 1$$$$1 \qquad 2 \qquad 1$$$$1 \qquad 3 \qquad 3 \qquad 1$$$$1 \qquad 4 \qquad 6 \qquad 4 \qquad 1$$$$\vdots$$`

---

Každý řádek začíná a končí jedničkou, každé z ostatních čísel lze vypočítat jako součet dvojice čísel ležících nad ním. Řádky i "sloupce" budeme indexovat od nuly. Za pomocí stromové rekurze napište funkci `pascal`, která vypočítá číslo na zadané pozici v Pascalově trojúhelníku.

```cs
pascal(0, 0) // -> 1
pascal(3, 1) // -> 3
pascal(3, 3) // -> 1
pascal(4, 2) // -> 6
pascal(5, 4) // -> 5
```

--

```cs
int pascal(int x, int y)
{
    if (x == 0 || y == x) return 1;

    return pascal(x - 1, y - 1) + pascal(x, y - 1);
}
```

---

## Děkuji za pozornost
