# Vorkurs

Lass uns zunächst die Grundlagen der Schulmathematik wiederholen. Am Ende des Kapitels kannst du dich mit einem [Video Quiz](#bereit-f%C3%BCr-die-universit%C3%A4tsmathematik) testen.

## Vorrangsregeln 

Was ist das Ergebnis von $3 - 5 : (2 \cdot (3 - 4) + 1)$? Eingeklammerte Bereiche werden zuerst aufgelöst, danach gilt "Punkt- vor Strichrechnung" (Multiplikation und Division vor Addition und Subtraktion). Gleichrangige Operationen werden von links nach rechts berechnet. 

<button class="button" onclick="reveal('button1')">Zu welchem Ergebnis kommst du?</button>

<div id="button1" class="solutionbox" style="display:none">
  \begin{align*}
    & 3 - 5 : (2 \cdot (3 - 4) + 1) \\ =&~ 3 - 5 : (2 \cdot (-1) + 1) \\ =&~ 3 - 5 : (-2 + 1) \\ =&~ 3 - 5 : (-1) \\ =&~ 3 - (-5) \\ =&~ 8
  \end{align*}
</div>

## Kommutativgesetz 

Für beliebige Zahlen $a$ und $b$ gilt $a + b$ = $b + a$ und $a \cdot b$ = $b \cdot a$. Man sagt dazu, dass Addition und Multiplikation *kommutativ* sind. 

<button class="button" onclick="reveal('button2')">Gilt das auch für Subtraktion und Division?</button>

<div id="button2" class="solutionbox" style="display:none">
Nein, denn zum Beispiel $1-2 = -1 \neq 1 = 2-1$ und $1:2 = 0.5 \neq 2 = 2:1$.
</div>

## Assoziativgesetz

Rechenoperationen, bei denen die Klammerung keinen Einfluss auf das Ergebnis hat, nennt man *assoziativ*. Das gilt wieder für Addition und Multiplikation, aber nicht für Subtraktion und Division: $a + b + c = a + (b + c) = (a + b) + c$ und $a \cdot b \cdot c = a \cdot (b \cdot c) = (a \cdot b) \cdot c$.^[Wenn Variablen im Spiel sind werden die Multiplikationspunkte häufig weggelassen: $a \cdot b = ab$. Bei zwei Zahlen führt das aber zu Verwirrung: $3 \cdot 3 \neq 33$.]

<button class="button" onclick="reveal('button3')">Gegenbeispiele, dass Subtraktion und Division nicht assoziativ sind?</button>

<div id="button3" class="solutionbox" style="display:none">
Zum Beispiel $1-(2-3) = 2 \neq -4 = (1-2)-3$ und $8:(4:2) = 4 \neq 2 = (8:4):2$.
</div>

## Distributivgesetz 

Wann hast du das letzte Mal ausgeklammert oder ausmultipliziert? Die Umformung $3x^2 - 6xy = 3x(x - 2y)$ nennt man *Ausklammern* (von $3x$), die Umformung $3(a+2b) = 3a + 6b$ *Ausmultiplizieren*. Die Rechtfertigung dafür liefert das Distributivgesetz: $a \cdot (b \pm c) = a \cdot b \pm a \cdot c$.^[Das Zeichen $\pm$ ist eine Kurzschreibweise und meint, dass beide Male Plus oder beide Male Minus eingesetzt wird.]

## Brüche

Brüche benötigen wir, wenn etwas Ganzes unterteilt wird: Eine Pizza wird in vier Stücke geschnitten, ich nehme mir eines weg, dann bleibt noch $\frac34$ der Pizza übrig. Die Zahl über dem Bruchstrich (hier die 3) nennt man *Zähler*, die untere Zahl (4) *Nenner*. Ein Bruchstrich ist das gleiche wie ein Divisionszeichen: $\frac34 = 3 : 4 = 0.75$.

<button class="button" onclick="reveal('button4')">Können Zähler oder Nenner den Wert Null haben?</button>

<div id="button4" class="solutionbox" style="display:none">
Der Nenner eines Bruches darf nie Null sein. Das ist gleichbedeutend damit, dass man nicht durch Null teilen darf. Der Zähler eines Bruches kann Null sein. In diesem Fall ist der Bruch gleich Null.
</div>

### Erweitern und Kürzen {-}

Wenn man Zähler und Nenner mit der gleichen Zahl multipliziert nennt man das *Erweitern* ($\frac34 = \frac{2\cdot 3}{2\cdot 4} = \frac68$), wenn man Zähler und Nenner durch die gleiche Zahl dividiert nennt man das *Kürzen* ($\frac24 = \frac{2:2}{4:2}=\frac{1}{2}$).

### Addition und Subtraktion von Brüchen {-}

Zwei Brüche können addiert (oder subtrahiert) werden, wenn sie den gleichen Nenner haben. Der Zähler wird dann addiert (oder subtrahiert), der Nenner bleibt der gleiche: $\frac14+\frac24=\frac{1+2}{4}=\frac34$ oder $\frac14-\frac24=\frac{1-2}{4}=-\frac{1}{4}$.^[Ein Minuszeichen im Zähler (oder Nenner) kann einfach vor den Bruch geschrieben werden: $\frac{-1}{4} = \frac{1}{4} = \frac{1}{-4}$.] Wenn die Brüche keinen gemeinsamen Nenner haben, müssen sie vorher erweitert werden: $\frac12+\frac13 = \frac36 +\frac26 = \frac56$.

### Multiplikation und Division von Brüchen {-}

Multiplikation von Brüchen ist einfacher, hier werden Zähler und Nenner jeweils multipliziert. Zwei Brüche werden dividiert indem ein Bruch mit dem Kehrwert^[Den Kehrwert eines Bruchs bildest du, indem du Zähler und Nenner vertauscht. Der Kehrwert von $\frac37$ ist also $\frac73$.] des anderen Bruches multipliziert wird.

<button class="button" onclick="reveal('button5')">Was ist das Ergebnis von $\displaystyle \frac15 + \frac{3:4}{5:2}$?</button>

<div id="button5" class="solutionbox" style="display:none">
\begin{align*}
& \frac15 + \frac{3:4}{5:2} = \frac15 +\frac{\frac34}{\frac52} = \frac15+\frac34\cdot\frac25 \\ =&~ \frac15+\frac{6}{20} = \frac{2}{10} + \frac{3}{10} = \frac{5}{10} = \frac12
\end{align*}
</div>

## Prozente 

Prozente sind spezielle Brüche, die immer den Nenner $100$ haben.^[Promille haben als Referenzwert die $1000$, nicht die $100$. Also sind $10‰ = 1\%$.] Zum Beispiel ist $1\% = \frac{1}{100}$ und $200\% = \frac{200}{100}=2$. 

<button class="button" onclick="reveal('button6')">Wenn $42$ genau $7\%$ sind, welcher Wert entspricht dann $100\%$?</button>

<div id="button6" class="solutionbox" style="display:none">
Wenn $42$ genau $7\%$ sind, dann sind $42/7=6$ genau $1\%$ und somit entspricht $6\cdot 100 = 600$ den $100\%$.
</div>

## Potenzen 

Es gilt

$a^0 = 1$

### Potenzgesetze

Sei $a > 0.$

\begin{equation}
a^{-r} = \frac{1}{a^r} (\#eq:pot1)
\end{equation}

\begin{equation}
a^{r+s} = a^r \cdot a^s (\#eq:pot2)
\end{equation}

\begin{equation}
a^{r-s} = \frac{a^r}{a^s} (\#eq:pot3)
\end{equation}

\begin{equation}
(a\cdot b)^r = \frac{a^r}{b^r} (\#eq:pot4)
\end{equation}

\begin{equation}
\left(\frac{a}{b}\right)^r = \frac{a^r}{b^r} (\#eq:pot5)
\end{equation}

\begin{equation}
(a^r)^s = a^{r\cdot s} (\#eq:pot6)
\end{equation}

Und wenn $a$ negativ ist? $(-a)^r = (-1)^r a^r$.

### Binomische Formeln 

Achtung: $(a+b)^2 \neq a^2 + b^2$. Es gilt nämlich

\begin{equation}
(a+b)^2 = a^2+2ab+b^2, (\#eq:binom1)
\end{equation}

\begin{equation}
(a-b)^2 = a^2-2ab+b^2,(\#eq:binom2)
\end{equation}

\begin{equation}
(a+b)(a-b) = a^2-b^2. (\#eq:binom3)
\end{equation}

<button class="button" onclick="reveal('button7')">Kannst du die erste Formel durch Ausmultiplizieren überprüfen?</button>

<div id="button7" class="solutionbox" style="display:none">
\begin{align*}
& (a+b)^2 = (a+b)(a+b) = a(a+b) + b(a+b) \\ =&~ a^2 + ab + ba + b^2 = a^2 + 2ab + b^2
\end{align*}
</div>

## Wurzeln

### Wurzelgesetze

## Logarithmen 

### Logarithmengesetze

## Gleichungen 

### Gleichungssysteme 

### Ungleichungen 

## Funktionen 

### Ableitungen

### Extremstellen 

### Integration 

## Summen- und Produktzeichen 

## Bereit für die Universitätsmathematik?

<div class="yt-container">
  <iframe class="responsive-iframe" src="https://www.youtube.com/embed/tgbNymZ7vqY"></iframe>
</div>


