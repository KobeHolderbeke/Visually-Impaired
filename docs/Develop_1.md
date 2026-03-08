# Develop phase 1
## Wat weten we al? 

Dat is de vraag die gesteld wordt om de ontwikkelingsfase van start te laten gaan. 

Er zijn al een reeks aan inzichten bekomen (zie Definition), welke zich uiten als streefpunten voor volgende prototype iteraties en al een preciezer beeld schetsen van het uiteindelijke prototype.

![COW](/img/DEV1.png)

Aan de hand hiervan worden enkele zaken schematisch voorgesteld om te dienen als referentie, grond om op verder te werken, manier om ideeën te visualiseren en algemene hulp tijdens het proces: 

### User Flow

![UF](/img/DEV2.png)

### Human-Product Interactions

![HPI](/img/DEV3.png)

### Informatiearchitectuur

De informatiearchitectuur dient bestudeerd te worden voor zowel de app als mogelijke controllers:

**App**

![IAA](/img/DEV4.png)

**Controller principe 1**

![IAC1](/img/DEV5.png)

**Controller principe 2**

![IAC2](/img/DEV6.png)

### Customer Journey

![CJ](/img/DEV7.png)

### Storyboard

De storyboard wordt verder verfijnd om meer aan te sluiten bij de huidige visie van context en gebruik van het product.

![SB](/img/storyboard.jpg)

### Hiërarchische taakanalyse

### Morfologische matrix

![MM](/img/Morfomatrix.jpeg)

---
## Hoe bouwen we hierop voort?

Echter resteren er nog veel vragen, welke meer onderzoek nodig hebben om beantwoord te worden. Deze onderzoeksvragen worden gerangschikt op mate van urgentie en ook in diezelfde volgorde getest. 

![COW](/img/DEV9.png)

Het bepalen van de beste input-methode wordt als meest kritisch genomen, aangezien door deze te testen ook enige mate van inzicht bekomen kan worden op de andere vragen en deze de grootste vormbepalende factor heeft. 

Welke functionaliteit noodzakelijk is, welke _nice to have_ en welke _elimineerbaar_ is, kan in enige zin bepaald worden doormiddel van **card sorting**, zonder dat deze functionaliteit al effectief aanwezig dient te zijn in de prototypes. Dit betekent dat ook deze vraag geïntegreerd kan worden in de eerste testfase. 

Voor een volledige beschrijving van de eerste testfase, zie Develop 1 – User Test Protocol.

Dit leidt tot de volgende vraag, namelijk wat de **MVP** _(Minimal Viable Product)_ van de prototypes is, om deze onderzoeksvragen te beantwoorden: 

![COW](/img/DEV10.png)

Twee inputopties worden overwogen op dit punt: 
- Pedalen
- Side Buttons 

Beide van deze worden uitgewerkt tot een prototype, voldoet aan de bekomen MVP:

---
## Prototype 1 - Pedalen:

**Cenceptualisatie**

![COW](/img/DEV11.png)

Bij de conceptualisatie van de pedalen wordt een antropometrische analyse uitgevoerd van het voetbereik in neutrale zitstand, welke ook bruikbaar kan zijn bij volgende iteraties/onderzoeken/...: 

De keuze van pedalen komt reeds uit vorige testen, waarbij dit een intuïtieve manier is om met de voet inputs te geven. De reden hierdoor is da bijvoorbeeld pianospelers dit kennen van de piano pedalen, dit is dus een metafoor van hun omgeving. 

Anderzijds wordt deze keuze gemaakt vanuit de design requierments. Het bied een lage cognitieve belasting omdat een pedaal gekend is bij de meeste mensen. Het idee is om 2 hoofd pedalen te ontwerpen die hoofdfuncties zullen uitvoeren. Dit is echter niet genoeg om alle functies te kunnen uitvoeren. Hierdoor ontstond het idee om een “CTRL” knop te maken net zoals bij een toetsenbord, waar combinaties worden gemaakt voor meer functies te verkrijgen.  

![COW](/img/DEV12.png)

**Prototyping**

![COW](/img/DEV13.png)

**Resultaat**

![COW](/img/DEV14.png)

---
## Prototype 2 - Side Buttons:

**Conceptualisatie**

![COW](/img/DEV15.png)

Dit prototype is gebaseerd op de rust positie van de gebruiker, hiermee wordt verwacht dat wanneer er geen input moet gegeven worden, de voeten niet van de controller moeten gehaald worden. Ook moet de voet zich niet verplaatsen naar een alternatieve input, want per voet zijn er twee inputs. 

Dit hangt vast aan de design requirement die stelt dat het product een lage cognitieve belasting moet hebben tijdens het gebruik. Doordat de voet niet constant op en af een input moet gezet worden, is dit zowel voor inputs geven als ergonomische rust positie een aangenamere keuze. Het constant moeten verplaatsen van de voeten kan een drempel zijn bij het pedalen prototype. Aan de hand van dit prototype is het de bedoeling om te testen welk van de twee principes het best zal zijn om als finaal input principe te nemen.

**Prototyping**

![COW](/img/DEV16.png)

**Resultaat**


![COW](/img/DEV17.png)

---
# Test resultaten

## App

De app is in deze fase grotendeels hetzelfde in vergelijking met de vorige fase. Uit de test zijn deze conclusies getrokken: 
- Eliminatie van bevestigingsschermen heeft geen negatieve invloed op taakvoltooiing, maar
  reduceert tijd om taak te voltooien in significante mate. Deze aanpassing blijft behouden.
- Partituur scanfunctie in app integreren. Er bestaan hier al voorbeelden van zoals
  https://scan-score.com/en/  
- Mogelijke verwarring van lijstopdeling in achterhoofd houden dit oplossen aan de hand van
  tabbladen. 
- Een geschreven handleiding toevoegen over alle nodige besturingsinfo van het product.

## Prototype 1

Uit de test van het opstellen bleek dat een aanhangsel niet zo intuïtief is. Alle respondenten konden de hoofddoos correct plaatsen maar wisten niet wat men met het aanhangsel (“ctlr” pedaal) moest doen. 

![Foto](/img/RES1.png)
