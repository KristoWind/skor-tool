# skor-tool
Sander Kristo Oscar Reading Tool

# Master of Applied AI Logbook

[TOC]

# Log
> | Week       | Student(en)        | Samenvatting van werk                        | Volgende week                              |
> |------------|--------------------|----------------------------------------------|--------------------------------------------|
> |     1      | Kristo, Oscar en Sander | Brainstormsessie over ideeën, ontwerpworkshop en onderzoek naar relevante informatie. | Onderzoek Domeinkennis (Kristo), Bestaande oplossingen (Oscar), Behoeftes doelgroep (Sander). Scenario/Storyboard uitwerken. Flow diagram maken. Basiskennis opdoen NLP technieken.|
> |     2      | Kristo, Oscar en Sander | Flowchart gemaakt, Level of Control opgezet, Storyboard uitgewerkt, Scraping van HTML en PDF files, Paper prototype gemaakt en uitgewerkt  | Details van AI modellen uitwerken, controle en impact van fouten, architectuur AI model opstellen  |
> |     3      | Kristo, Oscar en Sander | KeyBERT experimenten, Transformer experimenten, Controle en impact van AI, Uitwerking details van AI modellen, Paperprototype testing binnen de klas | Paper prototype testing buiten de klas, experimentatie met moeilijksgraad bepalen en verdere transformer modellen. Value alignment |    
> |     4      | Kristo, Oscar en Sander | Keyword extraction comparisons, Paper Prototype getest buiten de klas, SKORT Tool gemaakt. | Word difficulty, peer assessment voorbereiden, Tool uitwerken tot eerste iteratie doelen. |
> |     5      | Kristo, Oscar en Sander | Presentatie gemaakt voor peer-review, Feedback in het logboek geordend en bijgevuld, AI terminologie, PKE voor keyword extraction, onderzoek gedaan naar transfer learning naar keyword extraction, MoSCoW analyse opgesteld, laatste protoytpe V1 versie gemaakt voor vrijdag (eerste iteratie | Logboek aanvullen/aanpassen voor vrijdag, Python prototype testen met testpersonen |
> |     6      | Kristo, Oscar en Sander | Logboek aangepast/aangevuld, geëxperimenteerd met zelf trainbare modellen. | Kerstvakantie |

# Ideeën uit brainstormsessie en keuze
 - Automatische quiz generatie
 - Emotie binnen een tekst bepalen
 - Spraakherkenning met zoekfunctie voor een specifieke doelgroep
 - Papieren tekst inscannen voor samenvatten/highlighten/vertalen
 - Markeren van stukken die iemand niet begrijpt en relevante termen opzoeken op internet
 - Papieren tekst omzetten
 - Automatische vertaler
 - Tekstniveau bepalen 
 - "Woord-voor-woord" systeem snelheid bepalen aan de hand van moeilijksheidgraad
 - Systeem dat elk woord aanpast zodat het minder verwerktijd kost voor het brein
 - Dikgedrukt begin van elk woord voor snel door tekst lezen
 - Bias detector voor teksten
 - Witregel na een lastige zin
 - Kernwoorden/Kernzinnen uit de tekst halen
 - Meningen van feiten scheiden
 - Hyperlinks plaatsen op relevante termen
 - Spelfouten correctie vóór het lezen
 - Definities/Synoniemen vinden voor lastige woorden
 - Leestijd persoonlijk bepalen
 - Research papers samenvatten
 - Negatief/Positief annotatie bij persoon
 - Text to speech
 - Literatuurbespreking samenvatting maker
 - Eye tracker voor dyslexie


Uiteindelijk is, in overleg met de coach, ervoor gekozen om vier van de bovenstaande ideeën in één tool verwerken voor de eerste iteratie. Deze ideeën waren:
- Tekstniveau bepalen
- Leestijd persoonlijk bepalen
- Definities/Synoniemen vinden voor lastige woorden
- Kernwoorden/Kernzinnen uit de tekst halen

Deze combinatie van vier ideeën achten wij haalbaar binnen de beschikbare tijd voor de eerste iteratie en daarnaast achten wij het mogelijk om een passende doelgroep te kunnen kiezen. Bovendien denken wij door deze ideeën uit te werken, dat aan de beschikbare leerdoelen voldaan kan worden.   


# Definitie van succes 

**Team**

> | Definitie van succes | Mogelijke problemen | Grote risico's | Wat heb je nodig gerustgesteld te worden? |
> |----------------------|---------------------|----------------|-------------------------------------------|
> | Een gerealiseerd en werkend prototype, dat een daadwerkelijke oplossing kan bieden voor de wensen/problemen van de stakeholders. | Te brede projectscope, oplossing past  niet op de behoeftes van de doelgroep. | Geen of te weinig geschikte datasets aanwezig voor het probleem, werkdruk buiten het project om | Positieve feedback uit testsessies met proefpersonen, positieve feedback uit coaching sessies. Resultaten. | 

 - **Individueel (Kristo)**

 >| Definitie van succes | Mogelijke problemen | Grote risico's | Wat heb je nodig gerustgesteld te worden? |
 >|----------------------|---------------------|----------------|-------------------------------------------|
 >| NLP basis beheersen en het prototype begrijpen en werkend krijgen | Ik heb nog erg weinig kennis van NLP, dus technisch op masterniveau komen gaat veel tijd kosten | Hoge werkdruk | Positieve reactie vanuit de betrokkenen bij het project. |

 - **Individueel (Oscar)**

>| Definitie van succes | Mogelijke problemen | Grote risico's | Wat heb je nodig gerustgesteld te worden? |
>|----------------------|---------------------|----------------|-------------------------------------------|
>| Een bruikbare nlp toepassing gemaakt te hebben en deze goed beargumenteren / documenteren | Andere vakken / paper die tijd wegneemt van het project. Gemaakt product/project onder verwachting van coach/docenten | Ziekte(winter tijd), Drukte buitenom studie | Verwachting vanuit coach / docenten duidelijk te hebben.|

- **Individueel (Sander)**

>| Definitie van succes | Mogelijke problemen | Grote risico's | Wat heb je nodig gerustgesteld te worden? |
>|----------------------|---------------------|----------------|-------------------------------------------|
>|Een goede bijdrage leveren aan het realiseren van een werkend prototype, dat een daadwerkelijke oplossing kan bieden voor de wensen/problemen van de stakeholders. | Geen duidelijke doelstelling of afbakening, waardoor we verdwaald raken in de opzet en mogelijke opties binnen het project. | Te veel werk buiten het project om. | Een bevestiging van coach/docenten dat wij(of ik) goed op weg zijn. |

## Process Flow
### Huidig proces (Oscar)
1. Student vindt een paper op het web.
2. Student probeert de grootte, moeilijkheidsgraad en onderwerpen van de paper te bepalen.
3. Student begint de paper te lezen wanneer hij/zij deze geschikt acht.
4. Student leest in de paper een onbekende term.
5. Student zoekt de term op in een tweede tabblad (optioneel, als de student niet te lui is).
6. Student leest over de term op een externe website in het tweede tabblad.
7. Student gaat verder met het lezen van de paper.
8. Terug naar stap 2, totdat complete paper gelezen is.

### Toekomstig proces (Kristo)
1. De student vindt een paper op het web.
2. De tool berekent belangrijke informatie over de paper (leestijd, moeilijkheisgraad) en extraheert de lastige/belangrijke termen uit de tekst.
3. De student ziet in één opslag of de paper geschikt voor hem/haar is om te lezen
4. De student leest een onbekende term.
5. Per term kan de student de betekenis vinden binnen de tool ter verduidelijking.
6. De student gaat verder met het lezen van de paper

## Domeinkennis leerstrategieën HBO-studenten (Kristo)
### soorten leerstrategieën: oriënterend, begrijpend, analytisch en herhaald. 
https://www.havohbo.nl/wp-content/uploads/Teksten-lezen-en-leren.pdf 

Oriënterend lezen/zoekend lezen:
Oriënterend lezen wordt ook wel globaal lezen of zoekend lezen genoemd, omdat je je een indruk vormt van de tekst en op zoek gaat naar de structuur. In de praktijk is deze techniek vooral handig voor een eerste kennismaking met de tekst.

Begrijpend lezen: 
Bij begrijpend lezen gaat het erom dat je kind de tekst die hij leest ook echt begrijpt. Meestal toetst een leerkracht dat tekstbegrip met vragen en opdrachten. Die vragen kunnen gaan over de inhoud van een deel van de tekst.

Analytisch lezen: 
Analytisch lezen houdt in dat je probleemoplossend kunt nadenken door een probleem of vraagstuk vanuit verschillende invalshoeken te bekijken. Ook kun je snel hoofd- en bijzaken onderscheiden. Analytisch vermogen lijkt sterk op kritisch denken.

Herhaald lezen: 
Herhaald lezen van teksten bevordert het vloeiend lezen en automatiseren bij zwakke lezers. Het maakt niet uit of dezelfde tekst herhaald wordt gelezen of dat meerdere teksten worden gelezen. Waarschijnlijk is de grote hoeveelheid tijd die wordt gespendeerd aan lezen een van de cruciale componenten.

### Reden en doel van de tool
Highlighten en herlezen van stukken tekst biedt minimaal effect bij HBO studenten (Nationale Onderwijs Gids, 2013). Zelfoverhoring, oefenvragen en het over langere tijd verspreiden van leersessies zijn wel effectief.

Hoe effectief studenten leren hangt niet enkel af van de manier waarop ze een tekst benaderen: ‘Door het bevorderen van levensvaardigheden gaan studenten beter in hun vel zitten en worden zij sociaal en emotioneel vaardiger. Hierdoor zijn zij in staat om zichzelf te motiveren en verbeteren hun leerprestaties.’ (Hogeschool Leiden, 2021). Studenten hebben vaak de nodige stress, omdat ze vaak veel werken, een druk sociaal leven hebben en bezig zijn met sociale media (Dopmeijer, 2021). Daarnaast vinden studenten het lastig om hulp te vragen, hun gedrag te sturen, zich betrokken te voelen bij onderwijsactiviteiten en (kritisch) te communiceren in de collegezaal (Hogeschool Leiden, 2019). Studenten hebben verder vaak ondersteuning nodig om gemotiveerd te blijven (Crone, 2014) en ze kunnen extra vatbaar zijn voor depressieve klachten. Levensvaardigheden dragen bij aan studiesucces en motivatie om te leren. Zie Hoofdstuk 19 van Hoe Leren Studenten (Hogeschool Leiden, 2021) voor meer informatie over het investeren in studiesucces met behulp van levensvaardigheden.

Honoursstudenten in het HBO houden zich tijdens het leren bezig met of de theorieën, interpretaties en conclusies goed onderbouwd zijn met bewijs (Tijdschrift voor Hoger Onderwijs, 2014). Daarnaast stellen deze honoursstudenten gerichte doelen voor hunzelf. Honoursstudenten onderscheiden zich van reguliere studenten door een hogere mate van kritisch denken en zelfregulerend leren. Om reguliere studenten slimmer te maken is vanuit hunzelf een grote mate van interesse en motivatie nodig. Door informatie bij lastige woorden te plaatsen die de student kan bestuderen en bekritiseren, wordt de kans op interesse vergroot. Bij interesse komt vaak motivatie kijken, waardoor de docent vooral kan optreden als begeleider, zodat de student meer zelfgereguleerd kan studeren. 

Het doel van de te ontwikkelen tool is om interesse op te wekken in het eigen vakdomein bij studenten die minder motivatie hebben, waardoor ze beter gaan presteren. Met behulp van de tool wordt de stap kleiner om de betekenis en interpretatie van belangrijke en lastige woorden uit te zoeken. Zodra de studenten meer domeinkennis hebben is de leerstof beter te volgen en wordt sneller interesse en motivatie opgewekt bij de student, wat de studieprestaties bevorderd. Daarnaast is het doel om de concentratie van de student te waarborgen. Als de student elk woord dat hij/zij niet begrijpt moet opzoeken in de browser verliest de student telkens de concentratie. Door definities van belangrijke/lastige woorden in de tool weer te geven leest de student sneller, makkelijker en met bewaarde concentratie door de tekst.

### Bronnen
Dopmeijer, J.M. (2021). Running on empty. The impact of challenging student life on wellbeing and academic performance. Proefschrift. Amsterdam: UVA

Hogeschool Leiden (2019). Levensvaardigheden voor studenten. Leiden: Hogeschool Leiden, lectoraat Ouderschap & Ouderbegeleiding

Motivatie en leerstrategieën van honoursstudenten (2014): https://oadoi.org/10.5553/tvho/016810952014032001009 

Minimale voordelen van highlighten en herlezen van stukken tekst (HBO). Zelfoverhoring, oefenvragen en het over langere tijd verspreiden van leersessies zijn wel effectief: https://www.nationaleonderwijsgids.nl/hbo/nieuws/15139-markeren-van-studiestof-geen-optimale-leermethode.html 

Hoe leren studenten in het hoger beroepsonderwijs (Hogeschool Leiden, 2021): https://www.hsleiden.nl/binaries/content/assets/hsl/over-hl/hl-canon-hoe-leren-studenten.pdf 

## Bestaande oplossingen (Oscar)
Keybert python library lijkt erg makkelijk toe te passen.
https://github.com/MaartenGr/KeyBERT    
Informatie over alles van nlp met verschillende bronnen/libraries/tutorials  
https://github.com/keon/awesome-nlp    
Bert 101 uitleg  
https://huggingface.co/blog/bert-101  
Datasets:  
	https://github.com/LIAAD/KeywordExtractor-Datasets
https://github.com/LIAAD/KeywordExtractor-Datasets#Inspec
	https://github.com/LIAAD/KeywordExtractor-Datasets#Krapivin
	https://www.kaggle.com/datasets/kkhandekar/word-difficulty
	https://huggingface.co/datasets/memray/keyphrase/tree/main/kp20k


## Behoeftes doelgroep (Sander)
### Interviews met doelgroep

**Testpersoon 1**
 - Hoe ga je om met lastige termen in teksten?
    - Ik probeer eerst uit de zinnen rondom de term af te leiden. Als dit niet voldoende is,  
   voer ik de term in op Google, in de hoop een duidelijke betekenis te kunnen vinden.
 - Hoe bepaal je de moeilijkheidsgraad van een tekst?
    - Ik kijk voornamelijk naar gebruikte formules en de resultaten. Daarnaast lees ik de 
   abstract of intro om de moeilijkheidsgraad van de tekst in te kunnen schatten.
 - Zou je geïnteresseerd zijn in de voor jouw gepersonaliseerde leestijd voor teksten?
    - Ja, het helpt met het inschatten van de tekst. Als ik iets snel wil weten/begrijpen, 
    ben ik niet van plan 30 minuten te gaan lezen.
 - Zorgt het beter begrijpen van de tekst voor meer interesse rond het AI onderwerp?
    - Ja, als ik het beter begrijp kan ik er ook beter aan relateren, als je weet hoe iets 
   werkt dan krijg je der ook meer interesse voor. 

**Testpersoon 2**
 - Hoe ga je om met lastige termen in teksten?
    - Ik ben dyslectisch persoonlijk, dus ik lees er eerst een paar keer overheen en  
   probeer het uit de tekst te kunnen afleiden. Als het een Engelse term is vertaal ik het 
   eerst. Tenslotte zoek ik op Google naar de Nederlandse definitie. 
 - Hoe bepaal je de moeilijkheidsgraad van een tekst?
    - Ik denk dat ik zelf wel een redelijk niveau bezit, dus ik maak me niet zo druk over de 
              moeilijkheidsgraad van een tekst
 - Zou je geïnteresseerd zijn in de voor jouw gepersonaliseerde leestijd voor teksten?
    - Ja, ik denk dat een gepersonaliseerde leestijd praktisch zou zijn.
 - Zorgt het beter begrijpen van de tekst voor meer interesse rond het AI onderwerp?
    - Ik denk het wel, als de tekst beter te begrijpen is, is het makkelijker om verder te 
              gaan met het lezen van teksten betreffende hetzelfde onderwerp.

**Testpersoon 3**
 - Hoe ga je om met lastige termen in teksten?
    -  Ik zoek meestal de term direct op, om de definitie te kunnen achterhalen. Dan nadat ik het wat meer begrijp, lees ik het in de tekst nogmaals.
 - Hoe bepaal je de moeilijkheidsgraad van een tekst?
    -  Ik kijk naar de woordkeuze en de zinsopbouw, veel vaktermen duiden meestal aan 
               dat de tekst van een wat hoger niveau zal zijn
 - Zou je geïnteresseerd zijn in de voor jouw gepersonaliseerde leestijd voor teksten?
    -  Ja, het zou fijn zijn om te weten hoe lang je met een tekst bezig zou zijn. Bovendien 
               geeft de aanduiding dat je snel door een tekst heen kunt gaan een positieve 
               instelling voor de tekst. 
 - Zorgt het beter begrijpen van de tekst voor meer interesse rond het AI onderwerp?
    -  Als je tekst beter kunt begrijpen, geeft dit een positieve mindset rond het onderwerp 
               en zorgt voor meer leesplezier. Daarnaast wordt ik uit mijn concentratie gehaald als 
               ik meermaals termen op een browser moet opzoeken. Met behulp van de tool blijf        ik in mijn concentratie, wat me uiteindelijk positief beïnvloed rond de interesse van het onderwerp.


### Enquete binnen doelgroep

- Totaal aantal testpersonen: 34
- Opleidingsniveaus: HBO - WO - Master - Afgestudeerd
- Opleidingen: Business en economie - Techniek - CMD - Onderwijs en opvoeding - Geowetenschappen - Toegepaste wiskunde - Maatschappij en recht - Gezondheid - Gedrags- en bewegingswetenschappen - Geesteswetenschappen - Logistiek management

||Door eerst het abstract te lezen |Tekst skimmen |Resultaten/conclusie bekijken |Door te kijken waar de literatuur vandaan komt|Niet, ik begin gewoon met lezen|
|-----------------------------------------------------|-----|-----|------|-----|------|
|Hoe schat je de moeilijkheidsgraad van een tekst in? | 19x | 1x  | 1x   | 5x  | 13x  |    

| | Ja | Nee |
|-|----|-----|
|Heb je moeite met het lezen van Engelse teksten?| 6x | 28x |

| | Ja, met behulp van internet | Nee | 
|-|----|-----|
|Zoek je lastige termen op ter verduidelijking?| 30x | 4x |

| |Een schatting maken van de leesmoeilijkheidsgraad |Bepalen van de categorie van het artikel/boek |Verwante artikelen en boeken aanbevelen op basis van de categorie en onderwerp.|Markering van de kernzin van een alinea |Markeren van belangrijke afkortingen en jargon |
|-----------------------------------------------------------------------------------|----|----|-----|-----|-----|
|Welke van de volgende digitale hulpmiddelen zou je interessant en/of nuttig vinden?| 4x | 8x | 18x | 18x | 17x | 

## Nulmodel (Kristo)
Er is een nulmodel vastgesteld als maatstaf voor de performance bij keyword extraction. Indien SKORT beter presteert dan het nulmodel wordt de tool gezien als een goed model.

Het nulmodel wordt gedefinieerd door de 10 meest voorkomende woorden in de tekst die niet terug te vinden zijn in een lijst van 10.000 meestgebruikte woorden, te zien als kernwoorden. Als SKORT betere (human reviewed) kernwoorden vindt dan het nulmodel, wordt SKORT gezien als een goed presterend model.

## Pakket van Eisen

| Nummer | Categorie | Eis | Afkomstig van |
|--------|-----------|-----|---------------|
|   1    | Technisch | Het prototype van SKORT kan kernwoorden uit een tekst halen en deze highlighten | Doelgroep |
|   2    | Technisch | De leestijd voor de paper wordt berekend en is personaliseerbaar | Doelgroep | 
|   3    | Technisch | De moeilijksheidgraad voor de paper wordt berekend en aan de gebruiker getoond | Doelgroep |
|   4    | Technisch | Definities en Synoniemen van termen moeten in de tool op te zoeken of terug te vinden zijn | Doelgroep |
|   5    | Technisch | Gebruiker moet zelf woorden kunnen selecteren om definities over te krijgen | Doelgroep / Team  |
|   6    | Technisch | De student mag niet dommer worden van de tool; De tekst mag geen informatie verliezen | Opdracht |
|   7    | Technisch | Tool moet papers kunnen inlezen (en keywords extracten) van elke website (Scalability) | Team |
|   8    | Technisch | Gevonden kernwoorden moeten dicht, niet meer dan drie fout, bij de kernwoorden liggen die een gemiddeld persoon uit de doelgroep zou kiezen|Team|
|   9    | Technisch | Het SKORT model, voor keyword extraction, moet op gebied van performance beter presteren dan het vastgestelde nulmodel | Team |
|   10   | Ethisch   | Het SKORT model, voor keyword extraction, moet dezelfde prestatie kunnen leveren op verschillende talen. | Team |
|   11   | Ethisch   | Dataset voor kernwoordextractie moet bestaan uit teksten geschreven door een even verhouding aan mannen en vrouwen | Coach |
|   12   | Ethisch   | Gevonden kernwoorden mogen niet een bias hebben richting een bepaalde doelgroep | Team |
|   13   | Juridisch | Er mag geen informatie behouden worden over de ingeladen paper. | Auteursrecht |
|   14   | Juridisch | De gebruiker hoeft geen account aan te maken en  persoonsdata (IP-adres, naam etc.) wordt niet opgeslagen. | AVG |
|   15   | Juridisch | De gebruiker heeft het recht om zijn/haar gepersonaliseerde data (leestijd, moeilijksheidgraad) te laten verwijderen. | Recht op wissing |
|   16   | Organisatorisch | De gebruiker moet feedback kunnen teruggeven/delen aan de ontwikkelaars. | Doelgroep |
|   17   | Organisatorisch | Tool moet overzichtelijk zijn ingericht, zodat onboarding niet nodig hoeft te zijn. (Explainability)| Doelgroep |
|   18   | Organisatorisch | De SKORT tool wordt gemonitord en onderhouden door het team en zal niet worden uitbesteed | Team |

### MoSCoW Analyse
De volgende MoSCoW analyse is aan de hand van de bovengenoemde requirements opgesteld.


| |Must haves | 
|-|-------|
|1|Het prototype van SKORT kan kernwoorden uit een tekst halen en deze highlighten|
|2|De leestijd voor de paper wordt berekend en is personaliseerbaar|
|3|De moeilijksheidgraad voor de paper wordt berekend en aan de gebruiker getoond|
|4|Definities en Synoniemen van termen moeten in de Tool op te zoeken of terug te vinden zijn|
|6|De student mag niet dommer worden van de tool; De tekst mag geen informatie verliezen|
|7|Het SKORT model, voor keyword extraction, moet op gebied van performance beter presteren dan het vastgestelde nulmodel|
|8|De SKORT tool wordt gemonitord en onderhouden door het team en zal niet worden uitbesteed|
|9|Gebruiker moet zelf woorden kunnen selecteren om definities over te krijgen|


| |Should haves | 
|-|-------|
|10|Tool moet papers kunnen inlezen (en keywords extracten) van elke website (Scalability)|
|11|Er mag geen informatie behouden worden over het ingeladen paper.|
|12|De gebruiker moet feedback kunnen teruggeven/delen aan de ontwikkelaars.|
|13|Tool moet overzichtelijk zijn ingericht, zodat onboarding niet nodig hoeft te zijn. (Explainability)|

| |Could haves | 
|-|-------|
|14|Gevonden kernwoorden moeten dicht, niet meer dan drie fout, bij de kernwoorden liggen die een gemiddeld persoon uit de doelgroep zou kiezen|
|15|De gebruiker hoeft geen account aan te maken en  persoonsdata (IP-adres, naam etc.) wordt niet opgeslagen|
|16|Gevonden kernwoorden mogen niet een bias hebben richting een bepaalde doelgroep|

| |Won't haves | 
|-|-------|
|17|Dataset voor kernwoordextractie moet bestaan uit teksten geschreven door een even verhouding aan mannen en vrouwen|
|18|Het SKORT model, voor keyword extraction, moet dezelfde prestatie kunnen leveren op verschillende talen.|



## Level of control (Kristo)
Onze AI-oplossing valt heeft zowel human-control als computer-automation. Omdat de gebruiker zelf kan selecteren welke tools hij/zij wilt dat toegepast worden op de tekst. De gebruiker kan daarnaast ook feedback geven op de tool door bijvoorbeeld aan te geven welk woord de gebruiker belangrijk/lastig vind waar geen verdere informatie bij staat.

![Level of Control](Levelofcontrol.png)

## Flowchart (Oscar)
![Flowchart](Flowchart_week1.png)

## Storyboard (Sander)
![Storyboard](Storyboard.png)

- Doelgroep: Studenten (die papers lezen)
- Behoefte doelgroep: Het vereenvoudigen van het vinden van definities/omschrijvingen van vaktermen en lastige woorden in een paper
- Wat levert de oplossing: Een tool om eenvoudig definities/omschrijvingen van vaktermen en lastige woorden te kunnen lezen, daarnaast levert het algemene nuttige informatie over de paper (moeilijkheidsgraad, leestijd etc.)

## User problem statement (Oscar)  

![User Problem Statement](UserProblemStatement.png)

## Role of AI Concept (Oscar)  

![Role of AI Concept](RoleofAIConcept.png)

## Soorten mogelijke bias (Kristo)
Er bestaat een kans op bias in SKORT. Mogelijke soorten bias die vastgesteld kunnen worden bij het gebruik van SKORT zijn:

* Demografische bias: als SKORT getraind is op teksten van blanke mannen, andere teksten mogelijk anders geinterpreteerd kunnen worden en het model niet eerlijk handelt. Daarom is het van belang dat SKORT getraind is op teksten van mensen met verschillende demografische achtergronden.
* Sociaal-culturele bias:als SKORT is getraind op teksten afkomstig van mensen uit een bepaalde cultuur, het lastig kan zijn om teksten die voortkomen uit een andere cultuur eerlijk te benaderen. Daarom is het van belang dat SKORT getraind is op teksten van diverse culturen.
* Historische bias: als SKORT is getraind op teksten geschreven in een bepaald tijdperk, kan het moeilijk zijn om teksten geschreven in een ander tijdperk goed te begrijpen. Daarom is het van belang dat SKORT getraind is op teksten van diverse tijdperken.
* Taalbias: als SKORT is getraind op teksten geschreven in het Engels, is het lastig om teksten geschreven in andere talen goed te begrijpen. Daarom is het van belang dat er alleen Engelse teksten gebruikt kunnen worden in de tool.
* Bias in bronnen: als SKORT is getraind op teksten uit bepaalde bronnen, zoals tijdschriften of websites, kan de tool vooringenomen zijn ten opichte van ideeen of perspectieven die in de bron worden voorgesteld. Daarom is het van belang dat SKORT enkel gebruikt wordt om wetenschappelijke artikelen te versimpelen.

## Evaluatie van SKORT (Kristo)
SKORT zal gevalueerd worden door:
1. De betrouwbaarheid te controleren. Het is belangrijk dat SKORT consistent presteert op allerlei soorten teksten, rekening houdend met de soorten bias, en doet wat wij zeggen dat hij moet doen.
2. De nauwkeurigheid te controleren. Dit gaan we controleren door de tool te testen met verschillende soorten teksten en te kijken of de keywords en definities die SKORT genereerd juist zijn.
3. Het gebruiksgemak wordt geevalueerd door te controleren of de UI duidelijk en logisch is aan de hand van testsessies en of SKORT niet te langzaam werkt.

## Confusion matrix (Sander)

De confusion matrix hieronder laat de mogelijke uitkomsten voor de keyword extraction uit de applicatie zien. De True Positive en de True Negative zijn de toestanden waar we naar toestreven. We focussen ons zo veel mogelijk op het voorkomen van False Negatives. Bij deze uitkomst missen we mogelijke keywords die cruciaal kunnen zijn voor de tekst. False positives worden minder erg geschat in dit geval, doordat de daadwerkelijke keywords nog steeds gemarkeerd kunnen worden. Een overvloed van keywords zou later nog gefilterd kunnen worden. 

| Confusion matrix | Positieve voorspelling | Negatieve voorspelling |
|------------------|------------------------|------------------------|
| Positieve waarheid | **True positive** (Het gewenste resultaat): Woorden dat in de tekst zijn gemarkeerd zijn daadwerkelijk keywords | **False negative**: Een woord dat daadwerkelijk een keyword is in de tekst wordt niet gemarkeerd    |
| Negatieve waarheid | **False positive**: Er wordt een woord gemarkeerd, maar dit is geen keyword in de tekst.                        | **True negative** (Het gewenste resultaat): Woorden dat geen keywords zijn in de tekst worden niet gemarkeerd |

## Impact op de maatschappij (Sander)

Hoewel het hier gaat om een simpele reading tool, kan de tool toch een impact uitvoeren op de maatschappij. Een positieve impact zou hierbij ons doel zijn, waarbij studenten in staat zijn om de volledig functionerende tool te kunnen gebruiken om het lezen/begrijpen van papers te kunnen vereenvoudigen. Daarnaast hopen wij hiermee overige ontwikkelaars aan te sporen om ook taalverwerkingsprojecten op te starten om studenten te kunnen helpen. 
<br> Maar de tool kan ook een (theoretische) negatieve impact op de maatschappij hebben. Denk hierbij aan het gebruik van papers die op onreglementaire wijze zijn verkregen en in de tool worden geladen (piracy). Daarnaast bestaat de kans altijd dat de tool een datalek zou kunnen krijgen, waardoor gegevens van gebruikers op straat zouden kunnen belanden (privacy).
<br> Daarentegen achten wij de kans klein op deze negatieve impact, gezien de staat van het huidige prototype en de nog lange weg van ontwikkelen voor ons. Hierom stellen wij de impact op de maatschappij op LAAG.    


## Level of automation (Sander)

![Level of automation](AutomationLevel.png)

From (Sheridan & Verplank, 1978) 

Ons prototype valt onder Level 7. Het prototype voert automatisch het AI gedeelte in de achtergrond uit wanneer de tekst wordt ingeladen. Het is vervolgens aan de gebruiker om te selecteren welk gedeelte/opties te gebruiken of in te zien. 

## Ethische en juridische requirements (draft) (Kristo)
Er zijn een aantal ethische requirements waar de tool rekening mee moet houden. 

* Inclusiviteit: SKORT werkt voor verschillende soorten teksten, zodat het toegankelijk is voor een breed publiek.
* Privacy: er worden geen persoonlijke gegevens opgeslagen of gedeeld zonder toestemming.
* Transparantie: SKORT geeft aan hoe de tool werkt en wat de beperkingen zijn, zodat de gebruiker weet wat hij/zij kan verwachten.
* Rechten van intellectuele eigendom: SKORT gebruikt geen teksten zonder toestemming van de rechthebbende.

## Mogelijke ongewenste consequenties (Kristo)
Er zijn een aantal mogelijke ongewenste consequenties van SKORT.

* Onnauwkeurigheid: als SKORT onnauwkeurig is kan dit leiden tot verkeerde definities of een verkeerd begrip van de tekst. Dit kan leiden tot miscommunicatie of onnodige verwarring.
* Bias: als SKORT niet goed is afgestemd op verschillende soorten teksten kan dit leiden tot discriminatie of ongelijkheid in toegang tot informatie.
* Privacy-inbreuk: als SKORT onbedoeld persoonlijke gegevens opslaat of deelt zonder toestemming van de gebruiker, kan dit leiden tot een privacy-inbreuk.
* Verwarring: Als de tool onduidelijk is of als de uitleg van het model niet goed is, kan dit leiden tot verwarring bij gebruikers.
* Verlies van productiviteit: Als SKORT moeilijk te gebruiken is of als het te veel tijd kost om de resultaten te bekijken, kan dit leiden tot verlies van productiviteit.
* Negatief effect op de reputatie: Als SKORT fouten maakt of als er problemen optreden met de tool, kan dit leiden tot een negatief effect op de reputatie van SKORT.
* Onvoldoende toegang: Als niet iedereen toegang heeft tot SKORT, kan dit leiden tot ongelijkheid en oneerlijke behandeling.
* Financiële kosten: Als SKORT duur is om te gebruiken of te onderhouden, kan dit leiden tot financiële kosten voor gebruikers of organisaties.
* Incompatibiliteit met andere systemen: Als SKORT niet goed samenwerkt met andere systemen of programma's, kan dit leiden tot problemen met het gebruik van de tool of het uitvoeren van taken.

## Paper prototype (Week 2/3)

![Paper prototype](Paper_Prototype_v1.jpg)
![Foto testsessie](PPTestsessie.jpeg)

## SKORT logo en fail gracefully (Kristo)
Het logo van onze AI-tool ziet er als volgt uit.

![SKORT logo](../doc/SKORT_logo.jpeg)

Het logo is uniek en simpel. In de 'O' zit een vergrootglas gemonteerd en aan de 'T' zit een globaal wetenschappelijk artikel vast met enkele gele highlights.

Mocht het model niet werken, komt de volgende pop-up op het scherm.

![Fail gracefully](../doc/SKORT_failgracefully.png)

De foutmelding bevat humor, omdat het woord 'wrong' in deze zin een belangrijk woord is en dus gehighlight is. Het designpatroon is als volgt:
1. Load the results of the used tool.
2. Allowing the user to quit the loading.
3. Show results to user, or the pop-up if the tool doesn't work.
4. Create button for the user to optionally give feedback of the results.

## Keyword extraction comparison

text1 = "virtually enhancing the perception of user actions. This paper proposes using virtual reality to enhance the perception of actions by distant users on a shared application. Here, distance may refer either to space ( e.g. in a remote synchronous collaboration) or time ( e.g. during playback of recorded actions). Our approach consists in immersing the application in a virtual inhabited 3D space and mimicking user actions by animating avatars. We illustrate this approach with two applications, the one for remote collaboration on a shared application and the other to playback recorded sequences of user actions. We suggest this could be a low cost enhancement for telepresence"
- keywords1 =  ["telepresence", "animation", "avatars", "application sharing", "collaborative virtual environments"]

text2 = "Dynamic range improvement of multistage multibit Sigma Delta modulator for low oversampling ratios. This paper presents an improved architecture of the multistage multibit sigma-delta modulators (EAMs) for wide-band applications. Our approach is based on two resonator topologies, high-Q cascade-of-resonator-with-feedforward (HQCRFF) and low-Q cascade-of-integrator-with-feedforward (LQCEFF). Because of in-band zeros introduced by internal loop filters, the proposed architecture enhances the suppression of the in-band quantization noise at a low OSR. The HQCRFF-based modulator with single-bit quantizer has two modes of operation, modulation and oscillation. When the HQCRFF-based modulator is operating in oscillation mode, the feedback path from the quantizer output to the input summing node is disabled and hence the modulator output is free of the quantization noise terms. Although operating in oscillation mode is not allowed for single-stage SigmaDeltaM, the oscillation of HQCRFF-based modulator can improve dynamic range (DR) of the multistage (MASH) SigmaDeltaM. The key to improving DR is to use HQCRFF-based modulator in the first stage and have the first stage oscillated. When the first stage oscillates, the coarse quantization noise vanishes and hence circuit nonidealities, such as finite op-amp gain and capacitor mismatching, do not cause leakage quantization noise problem. According to theoretical and numerical analysis, the proposed MASH architecture can inherently have wide DR without using additional calibration techniques"
- keywords2 =  ["sigma delta modulators", "analog-to-digital converters ", "multistage ", "multibit quantizer", "dynamic range improvement"]

text3 = "An ontology modelling perspective on business reporting. In this paper, we discuss the motivation and the fundamentals of an ontology representation of business reporting data and metadata structures as defined in the eXtensible business reporting language (XBRL) standard. The core motivation for an ontology representation is the enhanced potential for integrated analytic applications that build on quantitative reporting data combined with structured and unstructured data from additional sources. Applications of this kind will enable significant enhancements in regulatory compliance management, as they enable business analytics combined with inference engines for statistical, but also for logical inferences. In order to define a suitable ontology representation of business reporting language structures, an analysis of the logical principles of the reporting metadata taxonomies and further classification systems is presented. Based on this analysis, a representation of the generally accepted accounting principles taxonomies in XBRL by an ontology provided in the web ontology language (OWL) is proposed. An additional advantage of this representation is its compliance with the recent ontology definition metamodel (ODM) standard issued by OMG"
- keywords3= ["enterprise information integration and interoperability", "languages for conceptual modelling", "ontological approaches to content and knowledge management", "ontology-based software engineering for enterprise solutions", "domain engineering"]

**Cosine similarity score**

|Rank|Extraction method| Cosim (text1) | Cosim (text2)| Cosim (text3)| Cosim (avg) |
|------|-----------------|--------|-------|-------|------|
|1|PKE SingleRank       | 1.42   | **1.44**  | 2.17  | **1.67** |
|1|PKE TopicalPageRank  | 1.42   | **1.44**  | 2.17  | **1.67** |
|3|PKE PositionRank     | 1.48   | 1.37  | 2.13  | 1.66 |
|4|PKE TextRank         | 1.25   | 1.2   | **2.22**  | 1.56 |
|5|KeyBERT              | **1.67**   | 1.41  | 1.38  | 1.49 |
|6|YAKE                 | 1.32   | 1.33  | 1.32  | 1.33 |
|7|PKE Kea              | 1.33   | 0.92  | 1.56  | 1.27 |
|8|PKE TfIdf            | 1.32   | 0.92  | 1.56  | 1.27 |
|9|PKE TopicRank        | 1.33   | 1.06  | 1.3   | 1.23 |
|10|PKE FirstPhrases     | 1.29   | 1.18  | 1.17  | 1.20 |
|11|PKE KPMiner          | 1.17   | 0.92  | 1.45  | 1.18 |
|12|SpaCy                | 1.19   | 0.72  | 0.84  | 0.92 |
|13|RAKE                 | 0.87   | 0.46  | 0.32  | 0.55 |

Bovenstaande tabel geeft de cosine similarity score (Lahitani et al., 2016) weer tussen de bestaande keywords van de drie eerder genoemde teksten en de voorspelde keywords van de vier keyword-extractors van hoog naar laag in gemiddelde score. De cosine similarity score geeft weer wat de afstand is tussen twee woorden (in dit geval echte keywords en voorspelde keywords). 

Uit de testresultaten blijkt dat de **performance** van PKE SingleRank gemiddeld het beste is op de gebruikte testdata. Bovendien bleek de PKE methodiek in zijn algemeen sneller te werken dan modellen als KeyBERT of YAKE, gezien de lagere **resource demands**. In termen van **explainability** en **model complexity** heeft PKE Singlerank een specifieke methode om keywords te extracten die gemakkelijker te begrijpen is dan het gebruik van een voorgetraind model als KeyBERT. PKE Singlerank werkt minder goed als het grote hoeveelheden tekst moet verwerken. Academische papers zijn relatief klein, dus PKE Singlerank is **scalable** genoeg voor ons onderzoek. Hierom is uiteindelijk besloten om PKE SingleRank toe te passen in het prototype als definieve keyword extraction methode. 

*Lahitani et al., 2016*: Lahitani, A. R., Permanasari, A. E., & Setiawan, N. A. (2016). Cosine similarity to determine similarity measure: Study case in online essay assessment. 2016 4th International Conference on Cyber and IT Service Management. doi:10.1109/citsm.2016.7577578 

## Text difficulty (Sander)

In iteratie 1 zijn een aantal text difficulty measures toegepast op een kleine dataset van 3 papers, ter verkenning en experimentatie. De measures in kwestie waren:

 <br>**Tokenized measures**
 - MATTR (Moving Average Type Token Ratio)
 - HD-D (Hypergeometric Distribution Diversity index)
 - MTLD (Measure of Textual Lexical Diversity )

 <br>**Syllables measures**
 - Flesch-reading index
 - SMOG-index

 De resultaten uit de tokenized measures waren hierbij als volgt:

|Measure|Paper 1|Paper 2|Paper 3|
|-------|-------|-------|-------|
| MATTR |0.8077 |0.7475 |0.8020 |
| HD-D  |0.8613 |0.8017 |0.8239 |
| MTLD  |88.82  |54.54  |85.86  |

Hieruit valt op te maken dat Paper 2 op alle drie measures lager scoort, wat logisch is gezien deze paper door een teamlid is geschreven in tegenstelling tot de andere twee papers. Daarnaast moet er opgemerkt worden dat de measures niet met elkaar vergeleken kunnen worden, gezien de gebruikte schaal van de drie measures niet met elkaar overeen komen.

Resultaten voor de syllables measures zullen in iteratie 2 nog volgen. Daarnaast zal er een grotere dataset worden gebruikt voor het testen van alle measures, om zo tot een betere definitieve measure voor text complexiteit te kunnen komen.

## Feedback van testpersonen op paper prototype binnen klas (Sander)

#### Testpersonen: MAAI studenten
##### Het paperprototype is duidelijk/voldoende compleet/voldoende gedetailleerd.
  - Tip: I'tje op highlight optie, waarop bepaald het model?
  - Tip: Uitleg over de moeilijkheidsbepaling zou handig zijn, waar is dit op gebasseerd?
  - Tip: Zet niet alle opties aan bij het begin
  - Tip: Mist info knopje
  - Tip: Ben vergeten het te proberen, maar kan je dan ook eerst op de definities klikken en dan pas op keywords
  - Tip: Applicatie is niet duidelijk, PDF heeft geen website (?????), Popup kan niet context zien
  - Tip: Kleur
  - Tip: Info knop voor moeilijkheidsgraad/keywords ontbreekt, knopje terug ontbreekt

  - Top: Duidelijk idee en overzichtelijk prototype 
  - Top: De applicatie geeft niet te veel opties en is lekker simpel
  - Top: Simpel maar duidelijk
  - Top: Prototype is redelijk simpel, geen onnodige knoppen en je komt er makkelijk doorheen
  - Top: Duidelijk
  - Top: Erg duidelijk en goed doorheen te lopen zonder uitleg
  - Top: Mooie details, duidelijk wat je doet
  - Top: Heel duidelijk
  - Top: Eenvoudig en overzichtelijk

##### Het achterliggende idee is goed.
 - Tip: Waarom de highlight/descriptie uit zetten, daar is de tool toch voor bedoeld?
 - Tip: Het zou fijn zijn om bij de definities van termen relevante papers te tonen
 - Tip: Het voegt niet heel veel toe aangezien ik keywords ook kan googlen
 - Tip: Misschien wat extra features toevoegen
 - Tip: Misschien fijn als je zelf een moeilijksheidgraad kan bepalen
 - Tip: Startscherm nog niet (????), hover was niet duidelijk, misschien wat meer kleur toevoegen
 - Tip: Misschien meer functionaliteiten
 - Tip: Meerdere documenten tegelijk

 - Top: Chill idee!
 - Top: Handige tool die het lezen van papers een stuk toegankelijker kan maken
 - Top: handig, ik zou het gebruiken
 - Top: Het idee is prima, weet alleen niet of ik het zou gebruiken?
 - Top: Leuk idee
 - Top: Snelle en relevante tool
 - Top: Heel duidelijk wat het idee is
 - Top: Heel bruikbaar
 - Top: Leert over nieuwe concepten

##### Het ontwerp is goed.
 - Tip: SKORT is zo'n random naam (?????)
 - Tip: Uitleg over moeilijkheidsgraad is niet te vinden
 - Tip: Maak het minder druk
 - Tip: Niet helemaal compleet nog
 - Tip: Krijg gelijk alle beschrijvingen van de keywords, terwijl ik er misschien maar één niet begrijp
 - Tip: Misschien meer aesthetic

 - Top: Minimalistisch en overzichtelijk
 - Top: De applicatie geeft niet te veel opties en is daardoor simpel en makkelijk te gebruiken
 - Top: Je hebt al weinig functionaliteit en dat maakt het een fijne en simpele tool
 - Top: Goed ontwerp
 - Top: Zelfde als eerste top
 - Top: Heel duidelijk


Doorgevoerde aanpassingen na deze feedbacksessie:
 - Infoknoppen zijn toegevoegd bij leestijd en moeilijkheidsgraad 
 - Knoppen voor terug en home zijn toegevoegd
 - Keywords poppen niet allemaal meer op na een klik op de button

## Feedback van testpersonen op paper prototype buiten klas (Kristo)

#### Testpersoon 1: student (21 jaar)
##### Het paperprototype is duidelijk/voldoende compleet/voldonde gedetailleerd.
  - Tip: Toolknop maken
  - Top: Complexiteit

##### Het achterliggende idee is goed.
 - Tip: Doelgroep bepalen
 - Top: Goed uitgewerkt

##### Het ontwerp is goed.
 - Tip: n.v.t.
 - Top: Duidelijk overzicht

#### Testpersoon 2: student (24 jaar)
##### Het paperprototype is duidelijk/voldoende compleet/voldonde gedetailleerd.
 - Tip: Optie tot filteren per opleiding
 - Top: Duidelijke user interface

##### Het achterliggende idee is goed.
 - Tip: n.v.t.
 - Top: Handige tool voor research

##### Het ontwerp is goed.
 - Tip: n.v.t.
 - Top: n.v.t.

#### Testpersoon 3: student (23 jaar)
##### Het paperprototype is duidelijk/voldoende compleet/voldonde gedetailleerd.
 - Tip: Relevante papers lijst
 - Top: Reading time/highlights

##### Het achterliggende idee is goed.
 - Tip: n.v.t.
 - Top: n.v.t.

##### Het ontwerp is goed.
 - Tip: n.v.t.
 - Top: Simpel

#### Testpersoon 4: Docent (34 jaar)
##### Het paperprototype is duidelijk/voldoende compleet/voldonde gedetailleerd.
 - Tip: Maak de layout vloeiend en gebruik geen Wikipedia als bron.
 - Top: Duidelijke user interface, vanzelfsprekend.

##### Het achterliggende idee is goed.
 - Tip: Maak de zoektocht makkelijk. Zoals suggesties?
 - Top: Gaat snel, direct resultaat.

##### Het ontwerp is goed.
 - Tip: Stijl. Kijk naar soortelijke als voorbeeld.
 - Top: If it ain't broke...

Aanpassingen die na deze feedbacksessie nog zijn doorgevoerd:
- Layout is wat overzichtelijker gemaakt, paper is nu te lezen op de linkerkant van de pagina, buttons bevinden zich op de rechterkant van de pagina.
- SciHub links zijn toegevoegd als optie voor inladen, zodat de gebruiker niet eerst nog de paper hoeft te downloaden als pdf.

## Feedback uit peer-review (16-12-2022)

- **A1**
   - Technische en functionele requirements goed uitgelegd, kan wel concreter. Verder miste juridische eisen, is het gebruik van sci-hub links wel zo handig?
   - Eisen zijn getoetst bij de stakeholders, eisen waren opzich goed opgesteld. 
- **A3**
   - Onduidelijk hoe deze oplossing tot stand is gekomen. Wel goed uitgedacht (flowchart, storyboard, impact of mistakes).
   - Niet duidelijk gemaakt welke keuzes zijn gemaakt, waarom dit paper prototype? Duidelijk welke iteraties zijn uitgevoerd, maar niet specifiek wat er aangepast is aan het prototype.  
- **A4**
   - Mogelijke beperkingen duidelijk toegelicht. 
   - Wij hebben hier niks over gezien, wel iets over ethiek. Ethiek is voor de context wel goed uitgewerkt. 
- **B1**
   - Success definition duidelijk weergegeven. Etische beperkingen benoemd
   - Voelt nog erg generiek, hoe maak je dit specifiek in je systeem? Ethische aspecten over nagedacht, maar nog geen handelingen voor uitgevoerd. Als je een eigen dataset maakt hoe voorkom je dan bias?  
- **B2**
   - In depth uitleg over modellen en ook goed verschillende methode vergeleken (10 stuks ofzo :O??!?!??!!)
   - Goed dat er veel verschillende modellen met elkaar zijn vergeleken!  
- **B3**
   - Het plan is om een eigen dataset te maken en is ook de meest betrouwbare bron. Kijk vooral op huggingface voor inspiratie.  
   - Jullie maken gebruik van bestaande modellen, wel tools gebruikt om dataset inzicht te krijgen. Naar ons idee nog niet heel veel gedaan met data preparatie.
- **B4**
   - Uitgebreide evaluatie met duidelijke argumentatie.
   - Bestaand model gebruikt, dus dit is moeilijk te beoordelen. Jullie hebben wel de modellen geëvalueerd. 
- **B5**
   - Indrukwekkend prototype met werkende functies. Design duidelijk, maar paper was klein en moeilijk te lezen. 
   - Prototype is getest, feedback is niet heel specifiek genoemd. Demo is al super goed! 


**Conclusie** 
<br> Over het algemeen was de feedback op onze presentatie positief, met name betreffende de uitwerking van het prototype. Wel werd er aangemerkt dat het leerdoel A3 en B3 nog duidelijker uitgelicht hadden kunnen worden. Uit de feedback hebben we tevens de volgende punten gehaald voor verbetering in de tweede iteratie en voor de ontwerpreview van 23 december:
 - Requirements moeten concreter opgesteld worden, met name kijken naar juridische eisen
 - Duidelijker noteren hoe het idee tot stand is gekomen en wat er is aangepast na elke testsessie met het prototype
 - Ethisch aspect moet in het algemeen beter aan bod komen
 - Het ontwikkelen en trainen van een eigen model, met ook een eigen dataset, zal in de tweede iteratie moeten worden aangepakt.  
