---
title: Lister
description: en introduktion til array og ArrayLister
layout: default
nav_order: 4
has_children: false
parent: Flow1 - Grundlæggende Programmering
permalink: /lists/
---

# Lister: Tabeller og lister - array[] og ArrayList
Ind til nu, har vi haft et 1:1 forhold mellem variabelnavn og værdi. Med tabeller og lister kan vi have **ét** variabelnavn til **mange** værdier.
På den måde kan vi begynde og håndtere større mængder data i vores kode.

[Læringsmål for ugen](./learningobjectives.md)

# Mandag
Dagens emne er datastrukturen array som er en samling af data/værdier.

#### Forberedelse
Læs i bogen "Learning Processing", Chapter 9: Arrays (22 sider)


[Bonusmateriale](./resources.md)

#### Efter lektionen
Efter mandagslektioner vil der i starten være øvelser, som man med fordel kan sidde med i Open Learning, hvor der vil være mindst en tutor til stede. Opgaverne skal IKKE afleveres.
[Opgaver](https://github.com/Dat1Cphbusiness/Mandagsopgaver/blob/main/4.md)

#### Kode vi skrev i lektionen

Eksemplet viser hvordan vi kan hive et tilfældigt element ud af en liste.
Det viser også en metode der returnerer det sidste element i listen
```java
String[] groupMembers = new String[4];


void setup() {
groupMembers[0] = "Tess";
groupMembers[1] = "Signe";
groupMembers[2] = "Tine";
groupMembers[3] = "Tobias";

String gm = getRandomGroupMember();
println(gm);
println(getLastGroupMember());
}

//Skriv en metode der kan returnere et tilfældigt element fra listen  

String getRandomGroupMember(){
int ranNum = (int)random(groupMembers.length);
return groupMembers[ranNum];
}

//Skriv en metode der kan returnere det sidste element i listen  

String getLastGroupMember(){
int index = groupMembers.length-1;
return groupMembers[index];
}
```

# Tirsdag
Vi samler op på mandagslektionen og kigger på hvad I skal nå inden onsdagslektionen.

#### Forberedelse:
- Log på [klassen zoom rum](https://cphbusiness.zoom.us/j/66755584856?pwd=RDRqZjBqSXBsTlR0QjRsTXh0UEFTUT09)  med dit cph login.
- Tjek at dit camera virker og er tændt når lektionen starter.

# Onsdag
ArrayList er lidt som en array, men den er mere avanceret og har en klasse som man skal inporteres. Vi kommer til at arbejde med mange andre af sådanne Java klasser, som alle bliver beskrevet i [Javas API dokumentation](https://docs.oracle.com/javase/7/docs/api/)
Java API'et indeholder dokumentation for alle Java klasser, fx. klasser til at arbejde med databaser, grafiske interfaces, load af filer, datoer og tid og datastrukturer som fx. ArrayList.
[Du kan læse om Java API'et her]([Læs om Java Application Programming Interface](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2013/02/CS101-1.3.5.3-Java-Application-Programming-Interface-API-FINAL.pdf)
)
#### Forberedelse:
1. [w3Schools: Kort om ArrayList](https://www.w3schools.com/java/java_arraylist.asp) 
2. [Coding with John: Array vs ArrayList](https://youtube.com/watch?t=1&v=NbYgm0r7u6o)

# Torsdag

- [Torsdagsopgave 3: arrays, ArrayList and String](https://cphbusiness.mrooms.net/mod/assign/view.php?id=765989)
- [Afleveringslink](https://cphbusiness.mrooms.net/mod/assign/view.php?id=765989)

# Fredag
Review af torsdagsopgaverne

**Husk Skuffeprojektet**: Integrer hvad du har lært om lister i denne uge
[SP1](../../projects/SP1/README.md#uge-4-lister)