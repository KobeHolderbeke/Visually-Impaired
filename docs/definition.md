## Definition
Het doel van de Definition fase is om een antwoord te vinden op de vraag:  

_“Hoe kunnen we de leercurve voor slechtziende muzikanten verkleinen door de haptische feedback te verbeteren en interactie zonder handen mogelijk te maken?” [Introductie](/)
_ 

Dit vindt plaats onder de vorm van twee waves, door het volgen van een vast proces (Methodologie): 
- Brainstormen _(Functies, vormgeving)_
- Schetsen _(Conceptuele uitwerking)_
- Prototypen _(Materialisatie)_
- Testen _(Validatie/verbetering/eliminatie, inzichten, N = 2)_

---
### Wave 1 

**Brainstorm** 

Er kon gewerkt worden met intuïtie, Discovery interviews en benchmarking om te veronderstellen wat het product zou moeten doen en hoe het er zoal zou kunnen uitzien. 

Eerst werden de functies bepaald: 

Het product moet de gebruiker in staat stellen de muziektrack, audiopartituur te kunnen: 
- Pauzeren
- Hervatten
- Doorspoelen
- Terugspoelen 

Voor de vormgeving waren relevante inzichten uit benchmarking dat compactheid een grote rol speelt en dat vaak gebruikgemaakt wordt van metaforen. _(vormen/functies van alledaagse producten die al bij mensen bekend zijn)._ 

Hierdoor kwam het idee van twee pedalen _(1 per voet)_, vergelijkbaar met gitaarpedalen: 

![PEDAAL](/DEF1.png)

**Schetsen** 

Rekening houdend met de vooropgestelde eigenschappen komt het schetsproces uit op 2 compacte indrukbare “blokjes”, geïnspireerd door gitaarpedalen. 

Zoals weergegeven bieden deze 2 pedalen genoeg inputmogelijkheden om de vooropgestelde functies te kunnen uitvoeren.

![SCHETSEN](/DEF2.png) 

**Prototypen** 

De materialisatie gebeurt vooral uit karton, met willekeurig gevonden houten blokjes als gewichten en versneden gipsplaatpluggen als veringen. Doormiddel van reliëf wordt aangeduid waar de voet moet geplaatst worden en deze worden met een marker in een contrasterende kleur ingekleurd voor gebruikers die nog kleuren kunnen waarnemen. 

Er wordt ook een Makey Makey kit gebruikt met als hoop functionaliteit aan het prototype toe te voegen. De draden worden met plakband bevestigd en gepositioneerd zodanig dat deze contact maken bij indrukking. 

![PROTOTYPE VISUAL](/DEF3.png) 

Bij een zelftest van het prototype werkt de Makey Makey zoals gewenst: bij aansluiting aan een laptop kan met de pedaal een video gepauzeerd en hervat worden. 

![ZELFTEST](/DEF4.png) 

De Makey Makey is echter beperkt in welke outputs het van zichzelf aan de laptop kan overbrengen, namelijk: left-click, spatie en de pijltjestoetsen. 

Er blijken andere inputs dan deze nodig te zijn om de gewenste functies te behalen. 

E.g. deze van Mediaspeler: 
- Pauzeren	    -	Spatie
- Hervatten	   -	Spatie
- Doorspoelen	 -	Ctrl + Rechtse pijl
- Terugspoelen	-	Ctrl + Linkse pijl 

De Makey Makey biedt geen Ctrl output. Om dit te omzeilen wordt een extra input converter programma geïnstalleerd _(PowerToys)_: 

![POWERTOYS](/DEF5.png) 

Bij het testen van de combinatie van de Makey Makey en PowerToys input converter, werkten de nieuwe inputs niet in Mediaspeler, noch in Spotify. Ook in Word was er geen werking.  

Dit betekent dat het testen van functionaliteit in deze fase beperkt wordt tot enkel pauzeren en hervatten en hiervoor in de volgende fase doormiddel van Arduino of het maken van een eigen mediaprogramma een andere oplossing moet gevonden worden.

**Prototypen – App** 

Het is een vaste constraint dat zowel muziektracks als audiopartituren door de gebruiker gekozen moeten kunnen worden. Echter is er geen enkele app waarin je van een nummer beide van deze opties kan selecteren.  

Er is wel een website met open-source code die partituurfiles omzet tot gesproken audiopartituren: https://www.talkingscores.org/.  

Met behulp hiervan zal dus een eigen app ontwikkeld moeten worden. 

Dit gebeurt in deze fase enkel theoretisch, in een Word document waarin alle inputs en outputs van de app beschreven staan. 

![APP WAVE 1](/DEF6.png) 

Deze app wordt mondeling getest, waarin een onderzoeker zich voordoet als de app.

**Testen (Zie ook Methodologie)** 

<ins>Protocol</ins>  

De usability, intuïtiviteit van plaatsen/gebruiken, (hoeveelheid) misinputs, comfort bij gebruiken en frustratie/terughoudendheid/angst/… tijdens gebruik worden gemeten/getest bij de pedalen. 

Voor de app wordt geobserveerd of de gebruiker ergens vast komt te zitten of stappen terug hoeft te nemen, welke emoties er zijn bij gebruik en of de gewenste taak voltooid kan worden. 

Ook het volledige stappenplan van hoe de test verloopt staat beschreven. 

_Voor een volledige beschrijving, zie Wave 1 Protocol_ 

<ins>Test</ins>

![Test 1](/DEF7.png) 

<ins>Report</ins>

Key takeaways 
- Gebruiker was terughoudend bij gebruik -> Product moet sterker aanvoelen
- Geen onderscheid tussen linker- en rechterdeel -> Signalisatie van volgorde
- Looping functie overwegen
- Tijdens spelen kunnen wisselen tussen muziektrack en audiopartituur overwegen
- Meerdere inputs per voet overwegen
- Betere rustpositie op pedalen welke misinputs vermijdt
- Meer weerstand van pedaal overwegen
- Assisterende stem bij frequente gebruikers kan annoyance vormen -> Aparte optie om deze uit
  te zetten
- Settings knop toevoegen
  
_Voor een volledige beschrijving, zie Wave 1 Report_

---
### Wave 2

**Brainstorm** 

De nieuwe inzichten/ideeën voor het prototype bekomen uit de eerste gebruikerstest worden in rekening genomen bij deze ideegeneratie, met name 2 inputs per voet, een neutrale, horizontale rustpositie, meer weerstand bij indrukking en een robuuster geheel.  

Ook wordt antropometrie nu toegepast. 

![Brainstorm 2](/DEF8.png) 

![Antropometrie](/DEF9.png)

**Prototypen** 

Zoals het eerste prototype wordt ook dit prototype gematerialiseerd uit vooral karton. Echter zijn het deze keer meerdere lagen op elkaar geplakt wat voor extra stevigheid zorgt. Ook is het veringmechanisme anders: hier worden elastieken (haarbandjes) gebruikt.

![Prototyping 2](/DEF10.png)

Aan de app wordt in het theoretische model een ‘Settings’-knop toegevoegd, alsook de optie om de spraakassistent aan/uit te zetten. 

**Testen (Zie ook Methodologie)** 

<ins>Protocol</ins>  

Dezelfde zaken als bij de vorige test worden opnieuw onderzocht, met nog een extra nadruk op de tekortkomingen van prototype 1. De loop van het onderzoek is voor een groot deel identiek. Zowel het eerste prototype (pedalen) als het nieuwe prototype worden getest.  

De prototypes worden onderling vergeleken op vlak van prestatie in de verschillende meetgebieden, zowel observerend als door de mening te vragen van de proefpersoon _(QAP)_. 

_Voor een volledige beschrijving, zie Wave 2 Protocol._ 

<ins>Test</ins>

Prototype 2 presteerde ondermaats bij de opstellingstest.

![TEST 2](/DEF11.png)

_QAP 
“Pedalen zijn makkelijk en compact.” 
“Prototype 2 is te complex, lomp en groot, maar betere druksensatie.”_ 

<ins>Report</ins>

Key takeaways 
- Balans vinden tussen complexiteit, functionaliteit en grootte
- Signaleer ordening, plaatsing en oriëntatie met textuur en vorm
- Eliminatie van intermediaire confirmatieschermen, met als substitutie “Return”-knop overwegen
  (App) 

_Voor een volledige beschrijving, zie Wave 2 Report._

---
### Convergence of waves

Gebaseerd op de takeaways van de 2 testen wordt een nieuw theoretisch prototype uitgewerkt om de Definition fase mee af te sluiten. 

![COW 1](/DEF12.png)

![COW 2](/DEF13.png)

