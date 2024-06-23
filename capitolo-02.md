# Metodi risolutivi
## Il discriminante di un'equazione di 2° grado
Per risolvere le equazioni di 2° grado è possibile usare la formula:

```{math}
x = \dfrac{-b \pm \sqrt{b^2-4ac}}{2a}
```

ma non è necessaria per determinare le sole soluzioni razionali. È di grande aiuto calcolare il *discriminante*, ovvero il valore numerico che, nella precedente formula, compare sotto il simbolo di radice. Convenzionalmente al discriminante si assegna la lettera $\Delta$ (*delta maiuscolo*) ed è uguale a: 

```{math}
\Delta = b^2-4ac
```

````{prf:example}
Il discriminante dell'equazione $2x^2+15x+12=0$ è 
```{math}
\Delta = (15)^2-4(2)(12)=129
```
````

## Come risolvere le equazioni di 2° grado complete
In base al valore del discriminante è possibile ottenere informazioni sulla natura delle soluzioni dell'equazione.

::::{grid}
:gutter: 3

:::{grid-item-card} $\Delta<0$
l'equazione non ha soluzioni razionali (in generale non ha soluzioni reali).
:::

:::{grid-item-card} $\Delta=0$
l'equazione ha una soluzione razionale (in realtà sono due soluzioni coincidenti).
:::

:::{grid-item-card} $\Delta>0$
l'equazione potrebbe avere due soluzioni razionali (in generale ha due soluzioni reali).
:::
::::

In caso di $\Delta=0$, se l'equazione si presenta nella 'nostra' forma canonica, allora il 1° membro dell'equazione è scomponibile come quadrato di binomio. Di conseguenza, detta un po´ impropriamente, sarà possibile ricondurre l'equazione di 2° grado a una equazione di 1° grado.

```{prf:example}
$9x^2-6x+1=0 \Leftrightarrow (3x-1)^2=0 \Leftrightarrow 3x-1=0 \Leftrightarrow x = \dfrac{1}{3}$
```

In caso di $\Delta>0$, se il valore del discriminante è un *quadrato perfetto*, allora l'equazione di 2° grado avrà due soluzioni razionali, in caso contrario le due soluzioni saranno irrazionali.

````{prf:definition}
Un **quadrato perfetto** è un numero intero che può essere espresso come il quadrato di un altro numero intero.

```{prf:example}
Il numero $121$ è un quadrato perfetto perché $\sqrt{121}=11$, di conseguenza $121=11^2$, mentre $30$ non lo è perché $\sqrt{30}$ è un numero irrazionale.
```
````

Se l'equazione si presenta nella 'nostra' forma canonica, allora il 1° membro dell'equazione è scomponibile come *trinomio notevole*. Di conseguenza sarà possibile ricondurre l'equazione di 2° grado a due equazioni di 1° grado.

```{prf:example}
$2x^2-3x+1=0 \Leftrightarrow (2x-1)(x-1)=0 \Leftrightarrow x = \dfrac{1}{2} \lor x=1$
```

```{prf:observation}
Le soluzioni delle equazioni di 2° grado **complete** sono sempre diverse da zero.
```

## Come risolvere le equazioni di 2° grado incomplete
Le equazioni di 2° grado incomplete possono essere classificate in: *monomie*, *binomie* (o *pure*) e *spurie*.

### Equazioni di 2° grado monomie
Le equazioni $ax^2=0$ sono dette *monomie* e hanno come soluzione $0$.

### Equazioni di 2° grado binomie (o pure)
Le equazioni $ax^2+c=0$ sono dette *pure*, per risolverle è necessario innanzitutto verificare se i segni di $a$ (coefficiente direttivo) e $c$ (termine noto) sono concordi o discordi. Se i segni sono concordi, ovvero se $a \cdot c >0$, allora l'equazione non ha soluzioni reali, di conseguenza non ha soluzioni razionali. Se i segni sono discordi, ovvero $a \cdot c<0$, allora l'equazione ha sicuramente due soluzioni opposte, in particolare se il binomio è scomponibile come differenza di quadrati (su $\mathbb{Q}$) allora esistono due soluzioni razionali.

```{prf:example}
$4x^2-25=0 \Leftrightarrow (2x+5)\cdot(2x-5)=0$ 

quindi 

$2x+5=0 \Leftrightarrow x=-\dfrac{5}{2} \quad \lor \quad 2x-5=0 \Leftrightarrow x=\dfrac{5}{2}$.
```

### Equazioni di 2° grado spurie
Le equazioni $ax^2+bx=0$ sono dette *spurie* e hanno due soluzioni delle quali una è sempre zero. Per determinare queste due soluzioni è sufficiente procedere con il raccoglimento della $x$.

```{prf:example}
$3x^2-5x=0 \Leftrightarrow x\cdot(3x-5)=0$ 

quindi 

$x=0 \quad \lor \quad 3x-5=0 \Leftrightarrow x=\dfrac{5}{3}$
```
