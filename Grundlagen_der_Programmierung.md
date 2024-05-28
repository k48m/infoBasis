## Grundlagen der Programmierung

### Recherchiere die Definition der Begriffe ’programming’, ’coding’, ’scripting’, ’hacking’. Was unterscheidet diese Begriffe voneinander?
Programming (Programmieren) Definition: Der umfassende Prozess des Entwerfens, Schreibens, Testens und Wartens von Software.
Ziel: Erstellung komplexer Softwarelösungen.
Sprachen: Java, C++, Python etc.

Coding (Codieren) Definition: Das Schreiben von Code in einer Programmiersprache.
 Fokus: Das eigentliche Schreiben der Codezeilen.
 Sprachen: Java, Python, JavaScript etc.

Scripting (Skripten) Definition: Schreiben kleiner Programme zur Automatisierung von Aufgaben.
Umfang: Spezifische, oft kleinere Aufgaben.
       Sprachen: Python, JavaScript, Bash etc.

Hacking (Hacken) Definition: Finden und Ausnutzen von Schwachstellen in Computersystemen. Ziel: Sicherheitslücken identifizieren, Systeme durchdringen.
       Ethik: Kann sowohl legal (ethisches Hacken) als auch illegal (böswilliges Hacken) sein.
       
Unterschiede: Programmieren ist umfassender als Codieren. Skripten ist auf spezifische Aufgaben fokussiert, oft kleiner und weniger komplex. Hacken konzentriert sich auf das Finden und Ausnutzen von Sicherheitslücken, oft über das reine Programmieren hinaus.

### Recherchiere die Definition der Begriffe ’Program’, ’Algorithm’, ’Code’, ’Application’, ’Software’, ’Script’. Was unterscheidet diese Begriffe voneinander.
Program (Programm)Definition: Eine Reihe von Anweisungen, die von einem Computer ausgeführt werden. Beispiel: Textverarbeitungsprogramm. 
Algorithm (Algorithmus) Definition: Eine Schritt-für-Schritt-Anleitung zur Lösung eines Problems. Beispiel: Sortieralgorithmus. 
Code (Code) Definition: Der Text in einer Programmiersprache, der Programme und Software erstellt. Beispiel: Quellcode in Python. 
Application (Anwendung) Definition: Software, die eine bestimmte Aufgabe für den Benutzer erfüllt. Beispiel: Webbrowser, Spiele. 
Software (Software) Definition: Sammelbegriff für Programme und Anwendungen auf einem Computer. Beispiel: Betriebssystem, Anwendungen. 
Script (Skript) Definition: Ein kleines Programm zur Automatisierung von Aufgaben. Beispiel: Automatisierungsskript in Bash. Unterschiede: Program: Spezifische Anweisungen zur Ausführung einer Aufgabe. Algorithm: Theoretische Methode zur Problemlösung. Code: Schriftliche Anweisungen in einer Programmiersprache. Application: Benutzerorientierte Software. Software: Überbegriff für alle Programme und Anwendungen. Script: Kleines Programm zur Automatisierung von Aufgaben. 

### Erkläre kurz die Fachbegriffe ’High Level Programming Language’, ’Assembly Language’, ’Machine Language’. Gib ein Beispiel fur jede Kategorie.
High Level Programming Language (Hochsprachen)
Definition: Programmiersprachen, die weitgehend von der Maschinensprache abstrahieren und menschenlesbar sind. Ist ermöglichen es Programmierern, komplexe Aufgaben mit einfachen Befehlen zu schreiben.
Beispiel: Python
2. Assembly Language (Assemblersprache)

Definition: Niedrigere Programmiersprache, die eine symbolische Darstellung der Maschinensprache verwendet. Sie ist spezifisch für eine bestimmte Prozessorarchitektur und erfordert das Schreiben von Anweisungen, die direkt auf die Hardware zugreifen.
Beispiel: x86-Assembler
3. Machine Language (Maschinensprache)

Definition: Die niedrigste Programmiersprache, die direkt von der CPU ausgeführt wird. Sie besteht aus binären oder hexadezimalen Anweisungen, die für Menschen schwer verständlich sind.
Beispiel: 11001001 (Binärcode für eine spezifische Maschinenanweisung).

### Was ist ein Compiler, was ist ein Interpreter? Welche Funktionen erfüllen diese?
Compiler Definition: Ein Compiler ist ein Programm, das den Quellcode einer Hochsprache in Maschinensprache (Binärcode) übersetzt, die vom Computer direkt ausgeführt werden kann.
Funktionen: Übersetzung: Wandelt den gesamten Quellcode auf einmal in ausführbaren Code um. Optimierung: Verbessert den Code, um die Ausführungseffizienz zu erhöhen.
Fehlererkennung: Erkennt Syntaxfehler und andere Probleme im Quellcode vor der Ausführung.
Beispiel: GCC (GNU Compiler Collection) für C/C++
Interpreter
Definition: Ein Interpreter ist ein Programm, das den Quellcode einer Hochsprache Zeile für Zeile liest, interpretiert und direkt ausführt.
Funktionen:
Direkte Ausführung: Führt den Code Zeile für Zeile aus, ohne den gesamten Quellcode vorher zu übersetzen.
Fehlererkennung: Erkennt und meldet Fehler während der Ausführung des Codes.
Flexibilität: Erlaubt schnelles Testen und Debuggen, da Änderungen sofort ausgeführt werden können.
Beispiel: Python-Interpreter für Python.

### Recherchiere und erkläre folgende Fachbegriffe: ’Datentyp’, ’Kondition’, ’Schleife’, ’Kontrollstruktur’, ’Funktion’, ’Klasse’, ’Pseudocode’
1.Datentyp
Definition: Art der Werte, die eine Variable annehmen kann.
Beispiele: Integer, Float, String, Boolean
       
2. Kondition (Bedingung)
Definition: Ausdruck, der wahr (true) oder falsch (false) ist.
Beispiele: if (x > 0), while (y != 10)
       
3. Schleife
Definition: Wiederholt Anweisungen solange eine Bedingung erfüllt ist.
Beispiele: for (int i = 0; i < 10; i++), while (n > 0)
       
4. Kontrollstruktur
Definition: Steuert den Programmfluss.
Beispiele: if, else, switch, for, while
       
5. Funktion
Definition: Benannter Codeblock, der eine spezifische Aufgabe erfüllt.
Beispiele:
def add(a, b): return a + b

6. Klasse
Definition: Vorlage für Objekte, definiert Attribute und Methoden.
Beispiele:

python

class Hund:
    def __init__(self, name):
        self.name = name
    def bellen(self):
        print("Wuff!")

7. Pseudocode
Definition: Vereinfachte, sprachunabhängige Beschreibung von Algorithmen.
Beispiel:

BEGIN
    SET total TO 0
    FOR each number FROM 1 TO 10
        ADD number TO total
    END FOR
    PRINT total
END

### Ein Datentyp ist eine abstrahierte Struktur, in welcher Daten unterschiedlichen Types gesammelt werden. Diese nutzen unterschiedliche Längen von Byte, um verschiedene Werte oder Buchstaben speichern zu können. Was sind gängige Datentypen über verschiedene Programmiersprachen wie C, Python und Java, und welche Länge nutzen sie?
C
char
   Länge: 1 Byte
   Beschreibung: Speichert ein einzelnes Zeichen.
   
int
   Länge: Typischerweise 4 Bytes (abhängig vom Compiler und der Architektur)
   Beschreibung: Speichert ganze Zahlen.
   
float
   Länge: 4 Bytes
   Beschreibung: Speichert Gleitkommazahlen mit einfacher Genauigkeit.
   
double
   Länge: 8 Bytes
   Beschreibung: Speichert Gleitkommazahlen mit doppelter Genauigkeit.
   
short
   Länge: 2 Bytes
   Beschreibung: Speichert kleinere ganze Zahlen.
   
long
   Länge: Typischerweise 4 oder 8 Bytes (abhängig vom Compiler und der Architektur)
   Beschreibung: Speichert größere ganze Zahlen.
   
long lon
   Länge: 8 Bytes
   Beschreibung: Speichert sehr große ganze Zahlen.

Python

Python ist dynamisch typisiert und verwaltet die Speicherzuweisung intern. Trotzdem gibt es grundlegende Datentypen:

int
   Länge: Variabel (Python 3 verwendet eine unbeschränkte Genauigkeit für ganze Zahlen)
   Beschreibung: Speichert ganze Zahlen.
   
float
   Länge: 8 Bytes
   Beschreibung: Speichert Gleitkommazahlen mit doppelter Genauigkeit (entspricht `double` in C).
   
complex
   Länge: 16 Bytes (besteht aus zwei `float` Werten)
   Beschreibung: Speichert komplexe Zahlen.
   
str
   Länge: Variabel (Speicherbedarf hängt von der Länge des Strings ab)
   Beschreibung: Speichert Zeichenketten.
   
bool
   Länge: 1 Byte (intern repräsentiert als `int`, entweder 0 oder 1)
   Beschreibung: Speichert Wahrheitswerte (`True` oder `False`).

Java

byt
   Länge: 1 Byte
   Beschreibung: Speichert ganze Zahlen im Bereich von -128 bis 127.
   
short
   Länge: 2 Bytes
   Beschreibung: Speichert ganze Zahlen im Bereich von -32.768 bis 32.767.
   
int
   Länge: 4 Bytes
   Beschreibung: Speichert ganze Zahlen im Bereich von -2^31 bis 2^31-1.
   
long
   Länge: 8 Bytes
   Beschreibung: Speichert ganze Zahlen im Bereich von -2^63 bis 2^63-1.
   
float
   Länge: 4 Bytes
   Beschreibung: Speichert Gleitkommazahlen mit einfacher Genauigkeit.
   
double
   Länge: 8 Bytes
   Beschreibung: Speichert Gleitkommazahlen mit doppelter Genauigkeit.
   
char
   Länge: 2 Bytes
   Beschreibung: Speichert ein einzelnes Unicode-Zeichen.
   
boolean
   Länge: 1 Bit (im Speicher wird jedoch typischerweise 1 Byte verwendet)
   Beschreibung: Speichert Wahrheitswerte (`true` oder `false`).

Diese Datentypen bieten eine Basis für die Speicherung und Manipulation von Daten in verschiedenen Programmiersprachen, wobei die genaue Speicherbelegung und die Art der Daten unterschiedlich sein können.

### Pseudocode folgt keiner spezifischen Syntax oder Semantik. Es wird lediglich zur intuitiven Erklärung von Algorithmen verwendet. Interpretiere folgenden Pseudocode-Beispiele. Erkläre was in jedem einzelnen Schritt passiert.
**Beispiel 1**

i ← 10

if i ≥ 5 then

i ← i − 1

else

if i ≤ 3 then

i ← i + 2

end if

end if

**Beispiel 2**

Require: n ≥ 0

Ensure: y = x

y ← 1

X ← x

N ← n

while N ̸= 0 do

if N is even then

X ← X × X

N ← N

2

else if N is odd then

y ← y × X

N ← N − 1

end if

end while

**Beispiel 3**

if i ≥ maxval then

i ← 0

else

if i + k ≤ maxval then

i ← i + k

end if

end if

**Beispiel 4**

Require: n ≥ 0 ∨ x ̸= 0

3

Ensure: y = x

n

y ⇐ 1

if n < 0 then

X ⇐ 1/x

N ⇐ −n

else

X ⇐ x

N ⇐ n

end if

while N ̸= 0 do

if N is even then

X ⇐ X × X

N ⇐ N/2

else[N is odd]

y ⇐ y × X

N ⇐ N − 1

end if

end while

### Prozedurales Programmieren
Prozedurales Programmieren ist ein Programmierparadigma, das sich auf die Erstellung von Prozeduren oder Funktionen konzentriert. Diese Prozeduren sind eine Abfolge von Anweisungen, die bestimmte Aufgaben oder Berechnungen durchführen. Das Hauptziel dieses Paradigmas ist es, den Programmablauf klar zu strukturieren und in einzelne, wiederverwendbare Einheiten zu zerlegen. Prozedurales Programmieren ist dadurch gekennzeichnet.
Sequentiell arbeitet: Der Code wird in einer bestimmten Reihenfolge ausgeführt.
Modular ist: Der Code wird in Prozeduren oder Funktionen aufgeteilt, die wiederverwendbar sind.
Lokale und globale Variablen verwendet: Variablen können innerhalb von Prozeduren oder global im gesamten Programm definiert sein.
Beispiele für prozedurale Programmiersprachen sind C, Pascal und Fortran.

### Deklaratives Programmieren / Imperatives
Deklaratives Programmieren beschreibt, was das Programm erreichen soll, ohne den genauen Ablauf vorzugeben (z.B. SQL, HTML). **Imperatives Programmieren** legt fest, wie etwas erreicht werden soll, indem es Schritt-für-Schritt-Anweisungen gibt (z.B. C, Java).

### Pattern Observer Singleton
Das Observer Pattern ermöglicht Objekten, automatisch über Änderungen in einem anderen Objekt informiert zu werden. Das Singleton Pattern stellt sicher, dass eine Klasse nur eine Instanz hat. Zusammen genutzt ermöglichen sie die Benachrichtigung mehrerer Objekte über Änderungen einer Singleton-Instanz.
