---
title: SP3
description: Bunden opgave hvor I afprøver teknikker til objektetorienteret analyse og design samt anvendelse af samarbejdsteknikker.
layout: default
has_children: true
parent: Studypoint Projekter
nav_order: 3
permalink: projects/SP3/
---

### SP3 Streamingtjeneste

- [opgavetekst](SP3.pdf)
- [opgavetekst mini](SP3mini.pdf)


## Assets
- [download billeder til film](billeder-til-film.zip)
- [download billeder til serier](billeder-til-serier.zip)


## Data

 - [download csv for film](film.txt)
 - [download csv for serier](serier.txt)


## Aflevering

- [Afleveringslink](https://cphbusiness.mrooms.net/mod/assign/view.php?id=766022)


## Præsentation
Da alle har lavet det samme projekt, skal hver gruppe vælge et emne relateret til deres projekt, som de gerne vil præsentere til review. 

I præsentationen vil vi gerne præsenteres noget viden I har fået under projektforløbet. 

Sørg for at forberede jeres præsentation, gerne med nogle slides. 

Fordel taletiden mellem alle gruppemedlemmer. SP3 godkendelse kræver at man deltager i præsentationen af projektet.



#### Emner

- **Objektorienteret analyse og design**: Formålet med objektorientering er at skabe synergi mellem domænet og løsningen.
Hvordan når man frem til et godt objektorienteret design? Hvilke metoder og teknikker findes og hvad er deres rolle hver især? Hvad opnår man i koden ved at anvende nedarvning/interfaces/polymorfi?
Fortæl om jeres brug af domænemodel og klassediagram i kodeprocessen. Kom også gerne ind på sekvensdiagrammer og use-cases, samt andre måder at nedbryde problemet på.

- **Samarbejde og Kommunikation** : Hvilke teknikker kan man anvende når man er flere om at kode et system? Hvad er konskekvensen hvis der ikke er god kommunikation i teamet? 
Hvordan sikres at alle har samme billede af hvad der skal kodes og ikke koder i hver sin retning eller oven i hinanden?
Hvordan strukturerede I arbejdet i jeres projekt? Brugte I git, pair programming, code with me eller andet? 

- **Kommunikation med brugeren**: hvilke måder findes der til at modtage input fra brugeren og give et output fra
systemet? Hvordan kan man holde grænseflade kode adskildt fra fx. logik? 
Hvordan ser interaktionen ud I jeres løsning?

- **Datapersistence**: Hvordan kan man sikre at den tilstand der er i et program ikke går tabt fra session til session?
Skal man gemme alle ændringer lige når de sker, eller venter man til sidst? Hvordan adskiller man den kode der tager sig af at persistere fra anden kode fx. logik eller brugerinterface.
Fik I bygget en skalerbar løsning i relation til datapersistens? Hvor nemt ville man kunne udskifte datalaget med et andet?
Hvilke udfordringer oplevede vi i forbindelse med persistering af data? Kom også gerne ind på anvendte og alternative datastrukturer.

- **Separation of concerns**: En af kongstankerne bag OOP er at hver klasse har ansvar for en del af koden, og at vi holder en løs forbindelse mellem ansvarsområder, sådan at vi forbedre muligheden for kodegenbrug, og undgår spaghetti kode.
Hvor i vores kode har vi eksempler på dette design princip?, hvor har I eksempler på det modsatte? Hvilke udfordringer stødte vi på da vi prøvede at følge princippet? Kom også gerne ind på navngivning.

- **Unit testing** I et større projekt, med mange features, skal det være hurtigt at teste om alt stadig virker som det skal. Hvordan kan man bruge unit test til dette? 
Hvordan arbejde I med tests og hvilken effekt havde den metode I valgte på processen?