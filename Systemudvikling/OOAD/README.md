---
title: OO analyse og design
description: modeling and designing a problemspace
layout: default
nav_order: 1
has_children: false
parent: Flow 3 - Systemudvikling
permalink: /Systemudvikling/OOAD/
---

Bemærk at rytmen er anderledes i denne uge: 

|mandag | tirsdag  | onsdag | torsdag | fredag|
|--- |----------| --- | --- | ---|
|Lektion | Lektion* | Lektion |  | Lektion|

* **Alle** lektioner denne uge er med fysisk fremmøde
 


# Matador projektet

Over de næste to uger forvandler klassen sig til en udviklingsafdeling i et spilfirma.
Vi har fået til opgave at kode spil-logikken til brætspillet Matador. 
Vi skal arbejde i sprints og i teams vil i levere hver jeres del af koden, som vi så sætter sammen efter hvert sprint.


**NB!** Din mødestabilitet er (som på enhver anden arejdsplads) vigtig for at opnå kontinuitet i din forståelse og for hele holdets produktivitet.


# Uge 1: OO analyse og design

I denne uge er målet at blive enige om et design som vi alle kan kode efter. Vi vil også tage hul på de første sprints.
Der er to dele i et design:

1. statisk design (hvilke klasser skal vi bruge?)
2. dynamisk design (Hvilke metoder skal der være og hvordan skal de kommunikere?)

[Læringsmål for ugen](./learningobjectives.md)


# Mandag
Vi foretager objektanalyse på kundekrav til Matadorspillet og tegner en domænemodel.
Senere vil domænemodellen udvikle sig til et klassediagram og fungere som en slags aftaledokument i implementeringsfasen.

### Projektmål:
-Fælles forståelse og vokabular for entiteterne i systemet.


#### Forberedelse
- [GeeksForGeeks:object oriented analysis and design](https://www.geeksforgeeks.org/object-oriented-analysis-and-design/)
- [PlantUML.com: domænemodeller](https://plantuml.com/object-diagram)
- [læs Kundekrav](https://github.com/Dat1Cphbusiness/MonopolyF24/wiki/Funktionelle-krav)

### Aflevering
[Upload gruppens domænemodel]()

# Tirsdag
**NB!** Fysisk fremmøde

 - Vi skal blive enige om en domænemodel og se hvordan man kommer fra domænemodel til klassediagram.
For at nå frem til det dynamiske design, skal vi bryde opgaven mere ned med use cases.

Den systemansvarlige har skrevet nogle på forhånd, som vi skal kigge nærmere på.

- Vi starter projektet op ved at klone Game

### Projektmål: 
- Fælles forståelse for det hvordan systemet skal opføre sig.
- Finde kode vi kan genbruge, og tilpasse den, så den adlyder usecase 1 og 2.

#### Forberedelse
[læs use cases: (ready on tuesday)](https://github.com/tessG/MonopolyF25/wiki/Use%E2%80%90cases)

# Onsdag
Vi har etableret vores projektkode med noget genbrugt kode som har to ting, vi skal bruge: mekanismer til _datapersistens_ og _brugerdialog_.
### Projektmål:
Bygge game loop: mekanisme til at skifte mellem spillere.

# Torsdag
Kontoret er tomt, alle arbejder hjemme. 

Se evt. video [Coding with John: unit testing](https://youtu.be/vZm0lHciFsQ).
### Træn unit testing
Test og find fejl i vores kode, og præsenter dem for afdelingen i morgen.
Hvordan ? [Se guide](../../guides/unittesting.md)


# Fredag
I gang med at bygge spillepladen

Vi introducerer unit testing med junit
#### Forberedelse
[Coding with John: unit testing](https://youtu.be/vZm0lHciFsQ)

### Projektmål:
- Vi har fundamentet til et turbaseret spil.
- vi har en spilleplade.
<!---->