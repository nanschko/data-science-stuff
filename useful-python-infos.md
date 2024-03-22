<table class="t1" width="746.5" data-cellspacing="0"
data-cellpadding="0">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td class="td1" data-valign="top"><p><span
class="s1">Modul</span></p></td>
<td class="td2" data-valign="top"><p><span class="s1">Ein File mit
Python-Code. Es enthält Definitionen (Funktionen, Klassen, Variablen)
und Statements (Instructions). Der Name des Moduls ist der File-Name
ohne der File-Extension (also ohne .py). Ich kann es auch als Skript
ausführen</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">Third-Party Module, die nicht zur Python Standard
Library gehören, können mit pip (python package manager) oder conda
installiert werden.<span
class="Apple-converted-space"> </span></span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">Mit print(dir(modulname)) kann ich schauen, welche
möglichen Objekte ein Modul hat (z.B. beim Modul Math den Logarithmus,
quadrieren etc.)</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span
class="s1">Package</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Ist eine
Kollektion von Python-Modulen</span></p>
<p><span class="s1">Definiert als ein Verzeichnis, das eine __init.py__
File enthält (kann leer sein)</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">Object</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">alles in Python
sind Objects. (auch Funktionen)</span></p>
<p><span class="s1">Jedes Object hat einen Wert (Value), eine Identität
und einen Type:</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">Identity ändert sich NIE (Adresse im Speicher, ID)</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">Type legt fest, welche Operationen mit dem Objekt ausgeführt
werden können &amp; welche Werte es haben kann</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">Value/Wert kann sich verändern bei mutable objects, bei
immutable objects nicht</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">Objekte können iterable sein, z.B. Strings, Range
Objekte, File Objekte<span
class="Apple-converted-space"> </span></span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span
class="s1">Value/Wert</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Der Wert wird
ausgegeben, wenn das Object ausgeführt wird. Der Value eines Objects
kann durch print(…) wiedergegeben werden</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">Variable =
Name</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Python nennt
Variablen Names. Es wird genutzt, um auf ein Object zu
verweisen</span></p>
<p><span class="s1">Variablen/Namen können an Objects gebunden werden,
z.B. name = object</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">es können auch mehrere Namen an ein Objekt gebunden
werden.</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span
class="s1">Konstante</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Variablen, die
ihren Wert nicht ändern</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">Argument</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">In Python bezieht
sich der Begriff "Argument" auf einen Wert, der an eine Funktion oder
Methode übergeben wird, wenn sie aufgerufen wird. Argumente dienen dazu,
Informationen an Funktionen zu übergeben, damit sie diese verarbeiten
können. Funktionen können eine oder mehrere Argumente akzeptieren, je
nach ihren Anforderungen. Zwei Haupttypen:</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">positional arguments<br />
Positionelle Argumente sind die häufigste Art von Argumenten. Sie werden
in der Reihenfolge übergeben, in der die Funktion sie
erwartet.</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">keyword arguments<br />
Schlüsselwortargumente sind Argumente, die explizit mit ihrem
Parameter-Namen an die Funktion übergeben werden. Dies ermöglicht es,
die Reihenfolge der Argumente zu ändern oder nur bestimmte Argumente zu
übergeben, ohne die Reihenfolge beachten zu müssen.</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1"> </span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span
class="s1">Statement</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Statements sind
alles, was eine (oder mehrere) Zeilen Python-Code bilden kann, im
Regelfall machen sie irgendwas. Beispiele: Loops,
Conditionals</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">Ein Set von Statements = Code Block</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">Conditional Statement: if … else …<span
class="Apple-converted-space"> </span></span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">Expression</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">= gibt einen
einzigen Wert aus. Expressions sind Kombinationen aus Werten, Variablen,
Operatoren und Function calls, die zu einem resultierendem Wert
ausgegeben werden.</span></p>
<p><span class="s1">Auch considered Statements genannt.</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">boolean
expression/logical expression</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Die Begriffe
werden synonym verwendet.<span
class="Apple-converted-space"> </span></span></p>
<p><span class="s1">Conditions werden evaluiert und je nachdem ob der
Wert true oder false ist, wird das Programm eine andere Operation
ausführen.</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">Indexing</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Zugang zu
Elementen in einer Sequenz (z.B. Liste,String,Tuple) bekommen via
Index<span class="Apple-converted-space"> </span></span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span
class="s1">Slicing</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Elemente einer
Sequenz extrahieren über Index, Syntax:<span
class="Apple-converted-space"> </span></span></p>
<p><span class="s1">Start:stop:step</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">Operator</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Symbol, das eine
Handlung symbolisiert</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">numerical Operators: +, -,*,**,/,%</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">string Operators: +, *, in, indexing (return 1 item, zB [1],
slicing (return multiple items zB [1:4]</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">boolean Operators: and, or, not (Boolean Wert v. Operand wird
umgekehrt)</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">Comparison operators: ==, !=, &gt;, &lt;, &gt;=,
&lt;=</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span
class="s1">Operands</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">an Ihnen führt der
Operator die Handlung aus und gibt das Ergebnis aus.</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">Literal</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">= die literale
Notation zur Darstellung eines festen (konstanten) Wertes z.B. 42, 0.1,
(numerische Literale) oder z.B. „Hello World“ (String
Literale)</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1"> </span></p></td>
<td class="td4" data-valign="top"><p><span class="s1"> </span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">(Object-)Type</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Jedes Objekt hat
einen Type in Python, der Type kann herausgefunden werden mit
type(„ABC“) oder type(1) usw.  Types die es gibt:</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">integer (ganze Zahl)</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">float (Kommazahl)</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">string“….“ (Zeichenkette, definiert durch““)</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">boolean (True, False: true entspricht 1, false entspricht
0)</span></p>
<p><span class="s3">o</span><span class="s2">   </span><span
class="s1">true + true = 2</span></p>
<p><span class="s3">o</span><span class="s2">   </span><span
class="s1">true + true + false = 2</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">list (Liste, definiert durch […])</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">tuple – nicht veränderbare Elemente in Klammer (…)
IMMUTABLE!!<span class="Apple-converted-space"> </span></span></p>
<p><span class="s4">·</span><span class="s1">      </span><span
class="s4">None</span></p>
<p><span class="s1"> </span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span
class="s1">Klasse</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Synonym für Type.
Beschreibung der Types:</span></p>
<table class="t2" width="549.0" data-cellspacing="0"
data-cellpadding="0">
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<tbody>
<tr class="odd">
<td class="td5" data-valign="middle"><p><span
class="s1">Bezeichnung</span></p></td>
<td class="td6" data-valign="middle"><p><span
class="s1">Abkürzung</span></p></td>
<td class="td7" data-valign="middle"><p><span
class="s1">Bedeutung</span></p></td>
<td class="td8" data-valign="middle"><p><span
class="s1">Beispiel</span></p></td>
</tr>
<tr class="even">
<td class="td9" data-valign="middle"><p><span
class="s1">integer</span></p></td>
<td class="td10" data-valign="middle"><p><span
class="s1">int</span></p></td>
<td class="td11" data-valign="middle"><p><span class="s1">ganze
Zahl</span></p></td>
<td class="td12" data-valign="middle"><p><span
class="s1">3</span></p></td>
</tr>
<tr class="odd">
<td colspan="4" class="td13" data-valign="middle"><p><span
class="s1">pizza_Ida = 1</span></p>
<p><span class="s1">print (pizza_Ida)</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">1</span></p></td>
</tr>
<tr class="even">
<td class="td9" data-valign="middle"><p><span
class="s1">float</span></p></td>
<td class="td10" data-valign="middle"><p><span
class="s1">float</span></p></td>
<td class="td11" data-valign="middle"><p><span
class="s1">Fließkommazahl</span></p></td>
<td class="td12" data-valign="middle"><p><span
class="s1">3.1</span></p></td>
</tr>
<tr class="odd">
<td colspan="4" class="td13" data-valign="middle"><p><span
class="s1">pizza_Felix = 1.5<br />
print (pizza_Felix)</span></p>
<p><span class="s1">1.5</span></p></td>
</tr>
<tr class="even">
<td class="td9" data-valign="middle"><p><span
class="s1">string</span></p></td>
<td class="td10" data-valign="middle"><p><span
class="s1">str</span></p></td>
<td class="td11" data-valign="middle"><p><span
class="s1">Zeichenkette</span></p></td>
<td class="td12" data-valign="middle"><p><span class="s1">“Paprika,
Salami“</span></p></td>
</tr>
<tr class="odd">
<td colspan="4" class="td13" data-valign="middle"><p><span
class="s1">(alle Anführungszeichen immer oben setzen)<br />
pizza_Stefanie = „Paprika, Salami, Thunfisch, Oliven“<span
class="Apple-converted-space"> </span></span></p>
<p><span class="s1">print (pizza_Stefanie)</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">Paprika, Salami, Thunfisch, Oliven</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">STRINGS ZUSAMMENZÄHLEN</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">salami_pizza = „Salami“ + „-„ + „Pizza“<br />
print (salami_pizza)</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">Salami-Pizza</span></p>
<p><span class="s1"> </span></p></td>
</tr>
<tr class="even">
<td class="td9" data-valign="middle"><p><span
class="s1">boolean</span></p></td>
<td class="td10" data-valign="middle"><p><span
class="s1">bool</span></p></td>
<td class="td11" data-valign="middle"><p><span class="s1">boolesche
Werte (Wahrheitswerte)</span></p></td>
<td class="td12" data-valign="middle"><p><span class="s1">True oder
False</span></p></td>
</tr>
<tr class="odd">
<td colspan="4" class="td13" data-valign="middle"><p><span
class="s1">pizza_Ben = False<br />
print (pizza_Ben)</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">False</span></p></td>
</tr>
<tr class="even">
<td class="td9" data-valign="middle"><p><span
class="s1">list</span></p></td>
<td class="td10" data-valign="middle"><p><span
class="s1">list</span></p></td>
<td class="td11" data-valign="middle"><p><span
class="s1">Liste</span></p></td>
<td class="td12" data-valign="middle"><p><span class="s1">[“Salami“,
“Margherita“]</span></p></td>
</tr>
<tr class="odd">
<td colspan="4" class="td13" data-valign="middle"><p><span
class="s1">pizza_Leo = [„Salami“,“Margherita]</span></p>
<p><span class="s1">print (pizza_Leo)</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">[‚Salami‘, Margherita‘]</span></p></td>
</tr>
<tr class="even">
<td class="td9" data-valign="middle"><p><span
class="s1">tuple</span></p></td>
<td class="td10" data-valign="middle"><p><span
class="s1">tuple</span></p></td>
<td class="td11" data-valign="middle"><p><span class="s1">Tupel
(Elemente nicht veränderbar)</span></p></td>
<td class="td12" data-valign="middle"><p><span
class="s1">(‘Pizza‘,‘Salat‘,‘Eis‘)</span></p></td>
</tr>
<tr class="odd">
<td colspan="4" class="td13" data-valign="middle"><p><span
class="s1">pizza_Thea = (‚Pizza‘,‘Salat‘,‘Eis’)</span></p>
<p><span class="s1">print (pizza_Thea)</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">(‚Pizza‘,‘Salat‘,‘Eis’)</span></p></td>
</tr>
</tbody>
</table>
<p><span class="s1"></span><br />
</p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">List</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">= Data Type in
Python.</span></p>
<p><span class="s1">Eine Liste ist eine (sortierte) Sammlung von
Objekten.</span></p>
<p><span class="s1">Der Wert einer Liste bzw. der Wert der Objekte kann
sich verändern = MUTABLE</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">List concatenation (z.B: Listen addieren) macht eine
neue Liste</span></p>
<p><span class="s1">List extension (z.B. list.extend) erweitert die
originale Liste</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">Integer;
String</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">= Data Types in
Python.</span></p>
<p><span class="s1">Beide sind IMMUTABLE. – Man kann sie nicht
verändern, es können nur weitere Strings/Integer Objekte generiert
werden.</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">Funktion</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Code-Blocks die
einen bestimmten Task ausführen </span><span class="s5"></span><span
class="s1"> sie akzeptieren 1 oder mehrere Argumente und geben einen
Wert aus</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">type(4) – gibt den Typ des Objekts in der Klammer
wieder</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">isinstance (3,int) – überprüft, ob Objekt Teil v. Type
ist</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">len(„acgt“) – Länge des Strings</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">input(„input value:  ……..“) – gibt Input von User wieder
(eintippen in Tastatur)</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">abs(-4) – gibt den Absolutwert wieder</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">mit def kann eine eigene Funktion definiert
werden<span class="Apple-converted-space"> </span></span></p>
<p><span class="s1">Funktionen können allein stehen</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">Wenn ich kein return statement am Ende der Funktion
setze oder nur „return“ ohne einen Wert festzulegen, wird NONE
ausgegeben</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">Eine Funktion soll entweder etwas machen oder etwas
returnen, nicht beides. Entweder sie ändert z.B. den Status eines
Objekts (Value in Liste ändern usw) und returnt None oder sie returnt
eine relevante Info/Wert.</span></p>
<p><span class="s1"> </span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span
class="s1">Methode</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Funktionen, die an
bestimmte Objekte gebunden sind. Methoden sind determiniert durch den
Type.</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">List methods:</span></p>
<p><span class="s3">o</span><span class="s2">   </span><span
class="s1">.append(7) – hinzufügen von hier z.B. 7 zu einer
Liste</span></p>
<p><span class="s3">o</span><span class="s2">   </span><span
class="s1">.pop() – entfernen v. einem Index &amp; neues Ergebnis
wiedergegeben </span><span class="s5"></span><span class="s1"> wenn
nicht definiert &amp; Klammer leer wird immer der letzte Index
entfernt<span class="Apple-converted-space"> </span></span></p>
<p><span class="s1">§</span><span class="s2">  </span><span
class="s1">Pop returnt den Wert, der entfernt wurde, print() gibt das
Ergebnis das Pop gemacht hat wieder</span></p>
<p><span class="s1">§</span><span class="s2">  </span><span
class="s1">Pop und append gehen schnell weil sie mit Ende der Liste
gemacht werden (konstante Zeit)</span></p>
<p><span class="s1">§</span><span class="s2">  </span><span
class="s1">Extend erweitert die Liste indem sie verschmelzen</span></p>
<p><span class="s1">§</span><span class="s2">  </span><span
class="s1">Append fügt in die Liste noch eine Liste mit Klammern
ein</span></p>
<p><span class="s3">o</span><span class="s2">   </span><span
class="s1">.strip – Leerzeichen und andere Whitespace-Zeichen am Beginn
und Ende einer Zeichenkette entfernt; gibt neue Zeichenkette ohne
Whitespaces zurück</span></p>
<p><span class="s3">o</span><span class="s2">   </span><span
class="s1">sort</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">String methods:</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">.count(„…..“) – zählt Element in Strings</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">„….“.upper() – schreibt den String in Großbuchstaben
um</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">„….“.isupper() – Boolean, ob Großbuchstaben vorliegen oder
nicht</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">namespace</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">In Python sind
"Namespaces" Räume, in denen Variablen und Namen für Objekte organisiert
werden. Sie dienen dazu, sicherzustellen, dass Namen eindeutig sind und
es keine Konflikte zwischen verschiedenen Teilen eines Programms gibt.
Python verwendet verschiedene Arten von Namespaces, um diese
Organisation sicherzustellen:<br />
<br />
</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">local namespace: wird in der Funktion definiert und ist nur
für diese Funktion sichtbar<br />
<br />
</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">global namesp.: auf der obersten Ebene (ganz oben) im Script
oder Modul. Alle Variablen und Funktionen, die auf dieser Ebene erstellt
werden, gehören zum globalen Namespace. Dieser Namespace ist für das
gesamte Modul oder Skript verfügbar und kann von überall im Code
aufgerufen werden.<br />
<br />
</span></p>
<p><span class="s1">·</span><span class="s2">      </span><span
class="s1">built-in-namesp.: eingebaute Funktionen und Objekte (z.B.
print, len, int, str)</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">Methoden existieren nur im object namespace, nicht
direkt zugänglich vom global namespace</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">fruitful / void
functions</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">fruitful
functions:</span></p>
<p><span class="s1">Sie geben einen Wert aus ohne eine Action zu
performen</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">void functions:</span></p>
<p><span class="s1">sie performen eine action aber geben keinen Wert
aus</span></p>
<p><span class="s1"> </span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">Higher order
function</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Funktionen, die
Funktionen als Argument übernehmen können oder eine Funktion als
return-result ausgeben</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">function parameter
/ function argument /<span
class="Apple-converted-space"> </span></span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">positional arg.</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">keyword arg.</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Parameter = eine
Variable in der Definition der Funktion</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">Argument = die Werte, die der Funktion übergeben
werden (z.B. Zahl)</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">Wenn Argument in gleicher Reihenfolge aufgerufen wie
Parameter in der Definition</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">Keyword Argument (z.B. RNAFlag=True), machen
eigentlich nur Sinn bei optional arguments sonst ist es zu viel
Schreibarbeit; müssen nicht wie positional arguments die gleiche
Reihenfolge haben<span
class="Apple-converted-space"> </span></span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">docstring</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">das erste
Statement in einer Funktion/Methode usw.<span
class="Apple-converted-space"> </span></span></p>
<p><span class="s1">ausgezeichnet durch drei “““……..“““</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">type
hints</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">sie zeigen den
beabsichtigten Type der Argumente &amp; den return value an </span><span
class="s5"></span><span class="s1"> Python ignoriert
sie</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">variable
scope</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">definiert die
Sichtbarkeit &amp; Lifetime von einer Variable</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span
class="s1">exception</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">= Python Object,
das einen Error präsentiert (z.B. raise), notwendig wenn man mit
Programm sowohl zip file als auch normales file aufrufen möchte<span
class="Apple-converted-space"> </span></span></p>
<p><span class="s1">Ist ein Runtime Error, d.h. er tritt während des
Ausführens v. Code auf</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">Traceback</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Ist ein Report,
der die Sequenz des Function Calls beinhaltet, welche im Code an einer
bestimmten Stelle gemacht wurden</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span
class="s1">iterable</span></p></td>
<td class="td4" data-valign="top"><p><span
class="s1">Datenstruktur/Objekt, das in einer Schleife (z.B. for loop)
durchlaufen werden kann, wobei man auf die Elemente nacheinander
zugreifen kann – Elemente werden schrittweise
verarbeitet</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">doctests</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">ein Modul in
Python, das dazu dient, Python-Beispiele in Dokumentation zu testen
(beruhen auf der Standardausgabe von Shell, werden dort ausgeschnitten
(oder kopiert) und als Docstrings eingefügt<br />
Doctest sucht nach Texteilen, die wie interaktive Python-Sitzungen
aussehen &amp; führt diese Sitzungen dann aus, um zu überprüfen, ob sie
genau wie gezeigt funktionieren</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">mit import doctest</span></p>
<p><span class="s1">doctest.testmod(verbose=True) kann ein Doctest
ausgeführt werden</span></p>
<p><span class="s1">Es gibt in VSCode eine eigene Funktion, um sie
auszuführen</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">unit
test</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Sind kleine Tests,
die dazu dienen, die einzelne Teile der Funktionalität der Software
überprüfen; sind automatisierte Tests</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">List
comprehension</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Evaluiert eine
Expression und erstellt eine neue Liste mit den Ergebnissen</span></p>
<p><span class="s1">Syntax: (expression for item in
sequence)</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">generator
object/expression</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Sehr ähnlich zu
list comprehension nur mit runden statt eckigen Klammern</span></p>
<p><span class="s1">im Gegensatz zu Listen, die alle Elemente
gleichzeitig im Speicher speichern, generiert ein Generator-Objekt die
Elemente auf Anfrage und speichert nur den aktuellen Zustand.<span
class="Apple-converted-space"> </span></span></p>
<p><span class="s1">Range verhält sich ähnlich</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">ASCII</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1"> </span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">modulo operator
%</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">gibt den Rest
einer Divison wieder, z.B: 9 % 3 = 0, 10 %3 = 1</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">dictionary</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">ist ein
TYPE</span></p>
<p><span class="s1">Wie ein Wörterbuch das Begriffe und deren
Bedeutungen verknüpft, enthält das Python-Dictionary Elemente, die mit
weiterer Information verknüpft sind. In Python spricht man
bei Dictionaries ganz Allgemein von Key-Value oder auch Schlüssel-Wert
Paaren.</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">Ich kann alle Data Types verwenden für Keys und
Values außer jene, die immutable sind</span></p>
<p><span class="s1">Dictionarys sind nicht geordnet, Reihenfolge ist
unterschiedlich</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">Jeder Dictionary-Key hat seinen Platz (adress) im
Speicher, und der Platz kann kalkuliert werden durch den Wert des
Keys</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">Keys müssen immutable sein, weil sich sonst durch
Änderung des Key-Values auch die Adress ändern könnte; also müssen Keys
tuple, integer oder string sein.</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span
class="s1">set</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">sind wie
Dictionarys aber nur mit Keys, keine Values; werden z.B. bei
Membership-Testing verwendet</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">file
objects</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1"> </span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span
class="s1">json</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1"> </span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">Konstante</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">sind Variablen,
die immer groß geschrieben sind und sich nicht verändern. Da Python
keine Funktion o.Ä. für Konstanten hat, werden diese einfach groß
geschrieben</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">öffentliche /
private Komponenten</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">öffentliche
Komponenten sind für alle sichtbar, sollen klar dokumentiert sein, haben
keinen Unterstrich z.B. bei funktion()</span></p>
<p><span class="s1"> </span></p>
<p><span class="s1">private Komponenten sind für internen Gebrauch z.B.
_hilfsfunktion(); Docstrings sind nicht so wichtig weil sie nicht für
die Nutzung außerhalb des Moduls/der Klasse gedacht sind</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span
class="s1">Lambda</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Sind anonyme
Funktionen; also Funktionen, die einfach keinen Namen haben</span></p>
<p><span class="s1">Syntax:</span></p>
<p><span class="s1">Lambda-Arguments: expression</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">* oder
**</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Werden verwendet
für item packing/unpacking</span></p>
<p><span class="s1">* für iterables</span></p>
<p><span class="s1">** für dictionaries/key word
notations</span></p></td>
</tr>
</tbody>
</table>
