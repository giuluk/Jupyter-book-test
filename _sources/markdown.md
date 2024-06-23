# Capitolo 1 - Le equazioni di 2° grado
## Forma canonica delle equazioni di 2° grado
Un'*equazione polinomiale* $p(x)=0$ è di 2° grado se il polinomio $p(x)$ è di 2° grado. In generale un'equazione di 2° grado, si presenta nella forma (canonica):

```{math}
:label: equazione2grado
ax^2+bx+c=0 \qquad a, b,c \in \mathbb{Q} \land a \neq 0
```

Se $b$ e/o $c$ sono uguali da zero, allora l'equazione di 2° grado si dice *incompleta*, altrimenti *completa*.

In questa appunti $a$, $b$ e $c$ sono numeri (coefficienti) razionali, tuttavia tale limitazione non è necessaria.

Un'equazione di 2° grado a coefficienti razionali può comunque essere sempre ricondotta a un'equazione di 2° grado a coefficienti interi. È sufficiente moltiplicare ciascun termine dell'equazione per il $mcm$ dei denominatori di $a$, $b$ e $c$.

*Esempio*
Sia $\dfrac{1}{3}x^2+\dfrac{5}{2}x-2=0$ un'equazione di 2° grado a coefficienti frazionari. Al fine di ottenere un'equazione equivalente ma a coefficienti interi è sufficiente calcolare il $mcm$ di $3$ e $2$ (rispettivamente i denominatori di $a$ e $b$, in questo caso $c$ è già un numero) e  moltiplicare tutti i termini dell'equazione per $mcm(3,2)=6$:

```{math}
\dfrac{1}{3}x^2+\dfrac{5}{2}x-2=0 \Leftrightarrow 2x^2+15x-12=0$
```

Oltre ai coefficienti interi, per una questione di praticità, le nostre equazioni polinomiali dovranno rispettare le seguenti condizioni:
1. il coefficiente direttivo deve essere un numero positivo. Qualora non lo fosse è sufficiente invertire tutti i segni dei termini dell'equazione.
2. $a$, $b$ e $c$ devono essere coprimi. Ovvero se $mcd(a,b,c)=n\neq 1$, allora semplificheremo tutti i coefficienti per $n$.

Questi accorgimenti non sono, in generale, necessari ma li adottiamo per avere delle equazioni "comode" con le quali operare.

### Esempio
Ridurre l'equazione $-\dfrac{6}{5}x^2+4x-\dfrac{2}{3}=0$ in un'equazione polinomiale a coefficienti interi.

1. Dato che l'equazione è a coefficienti frazionari, allora calcolo il $mcm$ dei denominatori e lo moltiplico tutti i termini dell'equazione per in modo da trasformarla, fatte le opportune semplificazioni, in un'equazione a coefficienti interi.
2. Dato che il coefficiente direttivo è minore di zero, allora cambio tutti i segni dei termini dell'equazione.
3. Dato che i coefficienti dei termini dell'equazione non sono coprimi, li divido per i massimo comun divisore

1. $mcd(5,3)=15$ quindi, a seguito delle moltiplicazioni, l'equazione diventerà $-18x^2+60x-10=0$
2. $a=-18$ quindi, dopo aver cambiato i segni, l'equazione diventerà $18x^2-60x+10=0$
3. $mcm(16,60,10)=2$ quindi, dopo aver fatto le divisioni, l'equazione diventerà $9x^2-30x+5=0$

Ricapitolando:

```{math}
-\dfrac{6}{5}x^2+4x-\dfrac{2}{3}=0 \Leftrightarrow 9x^2-30x+5=0$
```

## Come risolvere le equazioni di 2° grado complete

Per risolvere le equazioni di 2° grado complete esiste una formula generale che però utilizza l'estrazione di radice. Dato che il nostro obiettivo è quello di risolvere le equazioni di 2° grado solo con soluzioni razionali, eviteremo di fare ricorso a questa formula. Innanzitutto dobbiamo calcolare il discriminante dell'equazione di 2° grado. Convenzionalmente il discriminante si indica con la lettera delta maiuscola $\Delta$. Per ricavare questo valore è sufficiente procedere come segue: $\Delta = b^2-4ac$
Ad esempio il discriminante dell'equazione precedente è: $\Delta = (15)^2-4(2)(12)=129$

Se il valore del discriminante è minore di zero allora l'equazione non ha soluzioni razionali (più in generale l'equazione non ha soluzioni reali)
Se il valore del discriminante è uguale a zero allora l'equazione ha una soluzione razionale (in realtà sarebbe più corretto parlare di due soluzioni coincidenti). Come si fa a determianre questa soluzione? Se l'equazione si presenta nella forma "nostra" forma canonica allora vuol dire che quel trinomio altro non è che un quadrato di binomio, quindi una volta effettuata la scomposizione è possibile ricondurre l'equazione di 2° grado a una equazione di 1° grado (in termine formali è un po' impropria come spiegazione ma rende l'idea). 

*Esempio*

$9x^2-6x+1=0 \Leftrightarrow (3x-1)^2=0 \Leftrightarrow 3x-1=0 \Leftrightarrow x = \dfrac{1}{3}$

Se il valore del determinante è maggiore di zero allora l'equazione avrà due soluzioni reali distinte. Il nostro obiettivo è quello di determinare le sole soluzioni razionali. Infatti anche se l'equazione 2x^2+3x-1=0 ha due soluzioni, entrambe le soluzioni non sono razionali.
Per capire se l'equazione ha soluzioni razionali è sufficiente verificare che il discriminante sia un quadrato perfetto.

**Quadrato perfetto**
Un quadrato perfetto è un numero intero che può essere espresso come il quadrato di un altro numero intero. Ad esempio il $121$ è un quadrato perfetto perché può essere riscritto come $11^2$.

Se il discriminante non è un quadrato perfetto allota possiamo concludere che l'equazione di secondo grado ha due soluzioni irrazionali ma se il discriminante è un quadrato perfetto allora l'equazione ha esattamente due soluzioni razionali distinte (osservazione per numeri razionali si intendo i numeri interi e quelli espressi come rapporto di interi.

Osservazione finale
Le equazioni di 2° grado complete non hanno mai lo zero come soluzione.

## Come risolvere le equazioni di 2° grado incomplete
Per risolvere lee equazioni di 2° grado incomplete bisgona innanzitutto classificarle in:
- monomie - $ax^2=0$
- binomie (o pure) - $ax^2+c=0$
- spurie - $ax^2+bx=0$

### Equazioni di 2° grado monomie
Le equazioni di secondo grado monomie hanno come soluzione $0$.

### Equazioni di 2° grado spurie
Le equazioni di 2° grado superie hanno sempre due soluzioni razionali e una delle due soluzioni è sempre zero. Per determinare queste due soluzioni è sufficiente ricorrere al raccoglimento totale.

**Esempio**
$3x^2-5x=0 \Leftrightarrow x\cdot(3x-5)=0$ affinche il prodotto di quelo monomio per quel binomio sia zero significa che uno dei due fattori (o entrambi) sia uguale a zero. Quindi $x=0$ e $3x-5=0 \Leftrightarrow x=\dfrac{5}{3}$

### Equazioni di 2° grado binomie (o pure)
Per risolvere le equazioni di 2° grado spurie è necessario innanzitutto verificare se i segni di $a$ (coefficiente direttivo) e $c$ (termine noto) sono concordi oppure discordi. Se i segni sono concordi ($a \cdot c >0$) allora l'equazione non ha soluzioni reali, di conseguenza non ha soluzioni razionali. Se i segni sono discordi ($a \cdot c<0$) allora l'equazione ha sicuramente due soluzioni reali opposte, in particolare se il binomio è scomponibile come differenza di quadrati (su $\mathbb{Q}$) allora esistono due soluzioni razionali.

**Esempio**
$4x^2-25=0 \Leftrightarrow (2x+5)\cdot(2x-5)=0$ quindi $2x+5=0 \Leftrightarrow x=-\dfrac{5}{2}$ o $2x-5=0 \Leftrightarrow x=\dfrac{5}{2}$.

Here is a "note" directive:

```{note}
Here is a note
```

It will be rendered in a special box when you build your book.

Here is an inline directive to refer to a document: {doc}`markdown-notebooks`.


## Citations

You can also cite references that are stored in a `bibtex` file. For example,
the following syntax: `` {cite}`holdgraf_evidence_2014` `` will render like
this: {cite}`holdgraf_evidence_2014`.

Moreover, you can insert a bibliography into your page with this syntax:
The `{bibliography}` directive must be used for all the `{cite}` roles to
render properly.
For example, if the references for your book are stored in `references.bib`,
then the bibliography is inserted with:

```{bibliography}
```

## Learn more

This is just a simple starter to get you started.
You can learn a lot more at [jupyterbook.org](https://jupyterbook.org).
