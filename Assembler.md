# Assembler
Assembler
Ein Assembler ist ein Programm das Quellcode in Maschinencode Stufe von Code übersetzt. Er wird verwendet um menschenlesbaren Code in Maschinenbefehle umzuwandeln.

## High Level Programming Language
ist eine Programmiersprache die abstrakt ist und dem Programmierer erlaubt auf einem höheren Niveau zu arbeiten indem sie abstrakte Konzepte verwendet.
#### Beispiel: C, Java und Python.

## Assembler Language
Ist eine Programmiersprache, die Befehle in einer Form darstellt die für Menschen leicht lesbar ist, aber direkt von einem Prozessor ausgeführt werden kann. Sie wird verwendet um die Hardware direkt zu steuern und ist besonders nützlich für Anwendungen.
#### Beispiel: Betriebssysteme und eingebettete Systeme.

## Machine Language
Machine Language ist die Sprache, die ein Computer direkt versteht. Sie besteht aus einer Abfolge von Nullen und Einsen die die Befehle für den Computer darstellen.
#### Beispiel: Addition oder Speicherzugriff.

## Abstraktionsebene
 Es bezieht sich auf das Konzept komplexe Systeme in einfachere Teilsysteme zu unterteilen um sie besser verstehen und verwalten zu können. In der Informatik gibt es verschiedene Abstraktionsebenen die von hoher Abstraktion, wie Anwendungssoftware bis hin zu niedriger Abstraktion, wie Maschinencode, reichen.

## Abstraktion
Es bedeutet irrelevante Details zu entfernen und nur die wichtigsten Informationen beizubehalten. In der Informatik wird Abstraktion verwendet, um komplexe Systeme zu vereinfachen und sie leichter verständlich und handhabbar zu machen.

## Abstrahieren
Abstrahieren ist der Prozess bei dem irrelevante Details eines Problems oder Systems entfernt werden um die zugrunde liegenden Konzepte oder Muster zu identifizieren.

## Instanzieren
der Prozess des Lesens oder Angebens von Informationen, beispielsweise des Speichertyps und der Werte für ein Datenfeld.
Eine Klasse oder ein abstraktes Konzept in ein konkretes Objekt umzuwandeln, das in einem Programm verwendet werden kann.

## Instanz
Eine Instanz ist eine konkretes Auftreten einer Klasse in einem Programm es ist ein bestimmtes Objekt in einem Programm eine Instanz seiner Klasse.

## Hexadecima
Hexadezimal ist ein Zahlensystem, das nicht bis 10, sondern bis 16 zählt. Es verwendet die Zahlen 0-9 und die Buchstaben A-F, um Zahlen darzustellen. Es wird oft in der Informatik genutzt, um Binärzahlen einfacher zu schreiben.

## Was ist die ’Control Unit’ ?
Die Control Unit innerhalb einer CPU ist vergleichbar mit dem Dirigenten eines Orchesters. Sie koordiniert und synchronisiert die verschiedenen Instrumente (die Hardware-Komponenten), um sicherzustellen, dass sie im Einklang arbeiten und die Befehle der Software richtig ausgeführt werden. Kurz gesagt, sie ist das Steuerzentrum, das den gesamten Betrieb des Computers orchestriert.
![image](https://github.com/k48m/infoBasis/assets/168540271/360c3d11-b3c9-46a6-97ec-b0573eb27a16)

## Was ist die ’Arithmetic/Logic Unit’ ?
ist ein Teil der CPU, der für das Ausführen von mathematischen Operationen (wie Addition und Subtraktion) und logischen Operationen (wie Vergleiche und Entscheidungen) zuständig ist. Stell sie dir wie einen Taschenrechner vor, der in deinem Computer eingebaut ist und rechnet sowie logische Entscheidungen trifft, um die gewünschten Ergebnisse zu liefern.
![image](https://github.com/k48m/infoBasis/assets/168540271/eea57f0f-9822-4055-89f6-bfa0a2472b05)

## Was ist die ’Memory Unit’ ?
Die Memory Unit ist der Ort, an dem der Computer Informationen speichert, die er benötigt, um zu arbeiten. Es ist sein Gedächtnis, wo er Dinge temporär ablegt, während er arbeitet.
![image](https://github.com/k48m/infoBasis/assets/168540271/67f8dcce-310a-4080-9096-3d87d9817e12)

## Was sind Register, was sind Addressen?
Register sind wie kleine Schubladen innerhalb der CPU, in denen Daten kurzfristig gespeichert werden können. Sie sind extrem schnell, aber begrenzt in der Menge und Größe der Daten, die sie halten können.

Adressen sind wie Wegbeschreibungen zu bestimmten Speicherorten im Computer. Jeder Speicherplatz im Computer hat eine eindeutige Adresse, die es dem Prozessor ermöglicht, genau zu wissen, wo sich bestimmte Daten befinden, damit er darauf zugreifen kann.

### Beschreibe die verwendeten Fachbegriffe: ’Instruction’, ’Mnemonic’, ’Instruction Encoding’, ’In-struction Format’, ’OPCode’, ’Register’, ’Memory Address’
Instruction: Ein Befehl, den der Computerprozessor ausführt, wie zum Beispiel eine Rechenoperation oder ein Speicherzugriff.

Mnemonic: Eine Abkürzung oder ein symbolischer Code für eine Maschinenanweisung, der Programmierern hilft, Befehle leichter zu schreiben und zu verstehen.

Instruction Encoding: Die Umwandlung einer menschenlesbaren Anweisung (wie einem Mnemonic) in eine Form, die vom Computer verstanden werden kann.

Instruction Format: Die Struktur einer Maschinenanweisung, die angibt, wie die Befehle und Operanden in einem Befehl codiert sind.
OPCode: Ein Teil einer Maschinenanweisung, der den Befehlstyp angibt. Er bestimmt, welche Operation ausgeführt werden soll.

Register: Kleine Speicherbereiche in der CPU, die zur temporären Speicherung von Daten und Zwischenwerten verwendet werden, um schnelle Zugriffe zu ermöglichen.

Memory Address: Eine eindeutige Nummer, die einen bestimmten Speicherort im Computerspeicher identifiziert, verwendet, um Daten im Arbeitsspeicher (RAM) oder anderen Speichergeräten zu lesen oder zu schreiben.

### Beschreibe kurz die wichtigsten Instruktionskategorien: ’Arithmetic’, ’Move’, ’Shift’, ’Load’, ’Control’, ’Memory’
Arithmetic: Führt mathematische Operationen wie Addition und Subtraktion durch.

Move: Kopiert Daten von einem Ort zum anderen.

Shift: Verschiebt die Bits einer Zahl nach links oder rechts.

Load: Lädt Daten aus dem Speicher in ein Register.

Control: Steuert den Ablauf des Programms, z. B. durch Sprünge oder Schleifen.

Memory: Erlaubt direkten Zugriff auf den Speicher, einschließlich Lesen, Schreiben und Manipulieren von Daten.
   
### Für die Enumerierung der Register gibt es im Kontext von MIPS die Register Naming Convention.Erkläre wofür konkret die einzelnen Registers von 0 bis 31 verwendet werden.
$zero ($0): Immer Null.

$at ($1): Assembler Temporary Register.

$v0-$v1 ($2-$3): Rückgabewerte von Funktionen.

$a0-$a3 ($4-$7): Argumente für Funktionen.

$t0-$t9 ($8-$15): Temporäre Variablen.

$s0-$s7 ($16-$23): Gesicherte (saved) Register.

$t8-$t9 ($24-$25): Zusätzliche temporäre Register.

$k0-$k1 ($26-$27): Kernel Register.

$gp ($28): Global Pointer.

$sp ($29): Stack Pointer.

$fp ($30): Frame Pointer.

$ra ($31): Return Address.

![image](https://github.com/k48m/infoBasis/assets/168540271/a6d07743-9749-43f4-b089-8e0b0a04cc41)

### Beschreibe kurz den Aufbau einer beliebigen Instruktion bis ins wesentlichste Detail.
Eine Instruktion besteht aus einem Opcode, der den Befehlstyp angibt, Operanden, die die Daten oder Adressen für den Befehl darstellen, einem Adressierungsmodus, der angibt, wie die Operanden im Speicher gefunden werden, und Steuerbits, die zusätzliche Funktionen oder Bedingungen der Anweisung steuern.

ADDIU $0, $1, 5
AND $1, $1, $1
BNE $0, $0, 32
JUMP 8
#### Beispiele: Instruktionen und deren binäre Repräsentationen:
ADDIU $0, $1, 5

Opcode: 001001

RS (Source Register): 00001

RT (Target Register): 00000

Immediate: 0000000000000101

AND $1, $1, $1:

Opcode: 100100

RS: 00001

RT: 00001
    JAL              instr_index
00001100 00000000 00000000 00011010
Hex: C 1 9
10010000 00000010 00001000 11001001
Hex: 9 2 8 C 9
00000000 00000000 00010000 00010010
Hex: 1 1 2
00000000 10001000 00010000 00000111
Hex: 8 8 1 7
00111000 11001001 00001110 10110101
Hex: 3 8 C 9 D B 5
