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

!!!!!
## Was ist die ’Control Unit’ ?
## Was ist die ’Arithmetic/Logic Unit’ ?
## Was ist die ’Memory Unit’ ?
## Was sind Register, was sind Addressen?

## Beschreibe die verwendeten Fachbegriffe: ’Instruction’, ’Mnemonic’, ’Instruction Encoding’, ’In-struction Format’, ’OPCode’, ’Register’, ’Memory Address’
## Beschreibe kurz die wichtigsten Instruktionskategorien: ’Arithmetic’, ’Move’, ’Shift’, ’Load’, ’Control’, ’Memory’
## Für die Enumerierung der Register gibt es im Kontext von MIPS die Register Naming Convention.Erkläre wofür konkret die einzelnen Registers von 0 bis 31 verwendet werden.
## Beschreibe kurz den Aufbau einer beliebigen Instruktion bis ins wesentlichste Detail.

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
