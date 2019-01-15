---
section: Hjälptexter katalogisering
title: Verk
order: 17
date: 2019-01-10
tags:
- under arbete
- verk
--- 

## Verk

Beskrivningen av ett verk återspeglar det konceptuella innehållet i en resurs. Till beskrivningen av verket knyts information som ämne, klassifikation, språk och innehållstyp. Ett verk kan sedan ha en eller flera instanser, till exempel utgåvor. Läs mer om [Instans](https://libris.kb.se/katalogisering/help/instance). 

Ett verk är av en viss typ. Exempel på verkstyper är: text, ljud, stillbild, rörlig bild, multimedia, karta. Det går för närvarande inte att byta beskrivningens verkstyp.  

Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Vi rekommenderar att tills vidare skapa verket som lokal entitet. Vi återkommer med anvisningar för att skapa verk som länkbara entiteter. Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk/Text.  
Läs mer om [Verk och Instans](https://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).  

Denna hjälptext beskriver ett antal vanligt förekommande egenskaper, med utgångspunkt från exempel. För instruktioner om att länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/ "Anvisningar för katalogisering - RDA").

Se även [instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy)  

I de flesta fall ska informationen delas upp i olika egenskaper (jfr fält) och underliggande egenskaper (jfr delfält). I några undantagsfall är det nödvändigt att använda ISBD-interpunktion i inom en egenskap, för att separera uppgifter. Dessa fall visas genom exempel nedan. I övriga fall, lägg inte in ISBD-interpunktion för att avsluta en egenskap (fält). Använd vid behov klamrar inom egenskap (fält), enligt Anvisningar för katalogisering - RDA.

I vissa fall fungerar det ännu inte fullt ut att lägga till alla uppgifter som beskrivs i denna hjälptext. Arbete pågår med förbättra gränssnittet. För att anmäla fel, använd detta formulär för [felrapportering](https://docs.google.com/forms/d/e/1FAIpQLSfOChJOGDoHUQguSF83F5XyTZiQL-yU47nvcqb6qwNT9GX7Aw/viewform). För att lämna synpunkter, använd detta formulär för  [ändringsförslag](https://docs.google.com/forms/d/e/1FAIpQLScgz_0enebhBn6uB8xvowkDBB4ax_dbvaobLSFfqFMoty6eQg/viewform).  

### Innehåll  

| [Verk](#verk) |  |  | 
| ----------- |  ----------- |  ----------- |
| [Verkets titel](#verkets-titel) |  | [Ämne](#amne) | 
| [Medverkan och funktion](#medverkan-och-funktion) |  | [Målgrupp](#malgrupp) | 
| [Relationer till andra verk och ingående verk](#relationer-till-andra-verk-och-ingaende-verk) |  | [Innehållstyp](#innehallstyp) | 
| [Språk](#sprak) |  | [Sammanfattning av innehåll](#sammanfattning-av-innehall) | 
| [Genre](#genre) |  | [Anmärkning om akademisk avhandling](#anmarkning-om-akademisk-avhandling) | 
| [Klassifikation](#klassifikation) |  |  | 

### Verk   
   
#### Instans av Verk/Text  
* Instans av Verk/Text (instanceOf/Work/Text)  
  Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Vi rekommenderar att tills vidare skapa verket som lokal entitet. Vi återkommer med anvisningar för att skapa verk som länkbara entiteter. Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk/Text.  
Läs mer om [Verk och Instans](https://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).  

För att lägga till egenskaper under Instans av Verk/Text, klicka på plustecknet vid Instans av Verk/Text - Lägg till egenskaper under: Text. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

#### Verkets titel
 
Ange den föredragna titeln för verket här, vid behov. Följ [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck "Anvisningar för katalogisering - RDA").  
För översättningar och för verk som har givits ut under olika titlar på samma språk eller när samma titel har använts för olika verk, ska den föredragna titeln för verket anges.    

##### Verkets titel
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 ‡a)  
  "Originaltitel" för ett verk med primär medverkan anger du här.  
  Skriv in uppgiften.  
  ```Exempel: Soldier spy```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde och ange en siffra.  
  ```Exempel: Huvudtitel: En arbetsdag i skriftsamhället, fileringsvärde: 3```  
 
##### Verkets titel - huvuduppslag
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 ‡a)  
 "Originaltitel" för ett verk utan primär medverkande anger du här.  
Under Instans av Verk/Text, lägg till Uttryck av (plustecknet vid Instans av Verk/Text - Lägg till egenskaper under: Text, välj Uttryck av).  
Skapa verk som lokal entitet (plustecknet vid Uttryck av - Lägg till verk, välj Skapa lokal entitet, längst ner i sidorutan till höger), skriv "verk" i rutan Skapa lokal entitet. Klicka på Verk. Det läggs till under Uttryck av. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Har titel. Välj Titel.    
Skriv in uppgiften under Huvudtitel.  
```Exempel: Bibeln```
*	Uttryck av/Verk/Har titel/Titel/Deltitel  
(expressionOf/Work/hasTitle/Title/partName = 130 ‡p)  
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).  
Skriv in uppgiften.  
```Exempel: Nya testamentet```

##### Verkets titel - analytisk sökingång  
För att ange verk som ingår i det beskrivna verket, motsvarande fält 730 0/2 (analytisk sökingång) i marc:  
Under Instans av Verk/Text, klicka på plustecknet vid Verk (lägg till egenskaper under: Verk) och välj Har del. Följ sedan stegen ovan, från ”Skapa verk som lokal entitet”.  

##### Verkets titel - relaterade verk  
För att ange verk som är relaterade, men inte ingår i det beskrivna verket, motsvarande fält 730 0/_ (icke-analytisk sökingång) i marc:   
Under Instans av Verk/Text, lägg till Relation genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till egenskaper under: Text) och välja Relation. Välj typ Relation. Lägg till Entitet genom att klicka på plustecknet vid Relation (Lägg till egenskaper under: Relation), välj Entitet. Skapa verk som lokal entitet (plustecknet vid Entitet - Lägg till verk). Följ sedan stegen ovan, från ”Välj Skapa lokal entitet”.  

#### Medverkan och funktion  
* Medverkan och funktion  
  Under Medverkan och funktion anges relationer till de agenter som medverkar i verket, till exempel författare, översättare, illustratörer samt funktionskod för respektive agent. Relationer till utgivare (710) anges för närvarande också här.   
  Följ dessa instruktioner:  
  [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
    
* Medverkan och funktion/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 100 1/- ‡a)  
  Länka till entitet. Se [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance).  
 
* Medverkan och funktion/Primär medverkan/Funktion (contribution/PrimaryContribution/role = 100 ‡4)  
  Länka till entitet. Se [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance).  
  
* Medverkan och funktion/Medverkan/Agent/Person (contribution/agent/Person = 700 1/- ‡a)  
  Länka till entitet. Se [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance).  
  
* Medverkan och funktion/Medverkan/Agent/Organisation (contribution/agent/Organisation = 710 2/- ‡a, ‡4 pbl)  
  Länka till entitet. Se [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance). 
  
* Medverkan och funktion/Medverkan/Agent/Jurisdiktion (contribution/agent/Jurisdiktion = 710 1/- ‡a, ‡4 pbl)  
  Länka till entitet. Se [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance). 
 
#### Relationer till andra verk och ingaende verk  
* Relationer till andra verk (700 1/- ‡a, ǂd, ǂt)
  Se [Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).
* Ingående verk (700 1/2 ‡a, ǂd, ǂt)
  Se [Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).  

#### Sprak 
* Språk (language = 008/35-37)  
  Ange textens språk. För en text på svenska, ange svenska. För att ange originalspråk för ett översatt verk, se Originalversion/Verk/Språk.  
  Länka till entitet.  
  ```Exempel: svenska (swe)```   
  För att ange att texten är på flera språk, ange ytterligare en språkkod genom att klicka på plustecknet vid Språk (Lägg till språk) och söka fram ytterligare en entitet för ett språk och länka till den.   
  
##### Översättning  
För en översättning, ange även:  
* Språk/Språk/Benämning (Language/label = 240 ‡l)  
  Lägg till ytterligare en förekomst av Språk, under Språk (klicka på plustecknet vid Språk), skapa lokal entitet (klicka på Skapa lokal entitet längst ner i sidorutan till höger och lägg till Benämning (klicka på Lägg till egenskaper under: Språk).  
  Skriv in språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 240 ‡l.  
  ```Exempel: Svenska```  
  
För en översättning av ett anonymt verk (ingen Medverkan och funktion/Primär medverkan förekommer), ange även: 
* Uttryck av/Verk/Språk/Språk/Benämning  
(expressionOf/Work/language/Language/label = 130 ‡l)  
Lägg till eventuell benämning på språk som ska ingå i den föredragna titeln. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och välj Skapa lokal entitet. Lägg till Benämning (plustecknet vid Språk - Lägg till egenskaper under: Språk, välj Benämning.  
Skriv in uppgiften.  
```Exempel: Svenska```

* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  
  För att lägga till uppgiften, klicka på plustecknet vid Instans av verk/Text och välj Anmärkning: Språk. Välj fras från lista.  
  ```Exempel: objektet är/innehåller översättning```  
  
* Originalversion/Verk/Språk (originalversion/Work/language = 041 ‡h)  
  Ange det språk som en översatt text är översatt från. För en text som är översatt från engelska till svenska, ange engelska här.   
  Klicka på Lägg till egenskaper under: Text, välj Originalversion, klicka på plustecknet vid Originalversion, välj Skapa lokal entitet (längst ner i sidorutan). Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk. Sök fram språkentiteten och länka.  
  ```Exempel: engelska (eng)```  
För översättningar i flera led, länka först till det mellanliggande språket och därefter till originalspråket.  
  
###### Parallelltext  
(008/35-37 + 041 ‡a + ‡a)  
* Språk (language = 008/35-37) +
   Anmärkning: Språk: Objektet är/innehåller ej översättning (marc:languageNote = 041 0/- ‡a)
   Ange det första språket genom att länka till en entitet för språket, under Språk. Ange ytterligare en språkkod för parallelltexten genom att klicka på plustecknet vid Språk (Lägg till språk) och söka fram ytterligare en entitet för ett språk och länka till den. Ange sedan om parallelltexten är en översättning. Klicka på plustecknet vid Verk och välj Anmärkning: Språk. Välj Objektet är/innehåller ej översättning.    
   
###### Parallelltext och texten delvis översatt 
(008/35-37 + 041 0/- ‡a + 041 1/- #a ‡h)  
* Språk (language = 008/35-37) +
   Anmärkning: Språk: Objektet är/innehåller ej översättning (marc:languageNote = 041 0/- ‡a)   
* Har del/Verk/Språk (hasPart/Work/language = 041 ‡a) +  
  Anmärkning: Språk: Objektet är/innehåller översättning (marc:languageNote 041 1/-) +  
  Originalversion/Verk/Språk (originalVersion/Work/language = 041 ‡h) 
  
  För att ange att texten delvis är översatt, till exempel när en publikation innehåller parallelltext, det vill säga är på två språk och den ena texten är en översättning: ange först Språk under Instans av Verk (se Språk ovan). Sök fram och länka till entiteten för det språk som inte är en översättning. Klicka sedan på plustecknet vid Verk och välj Anmärkning: Språk. Välj Objektet är/innehåller ej översättning.   
 Lägg sedan till Har del under Instans av Verk. Skapa verk som lokal entitet (plustecknet vid Har del - Lägg till resurs. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Verk och välj ++++ Verk.) Klicka på plustecknet vid den lokala entiteten Verk (Lägg till egenskaper under: Verk) och välj Språk. Sök fram och länka till entiteten för språket som texten är översatt till. Under den lokala entiteten Verk, lägg till Anmärkning: Språk och ange att resursen är/innehåller en översättning. Under Har del, lägg till Originalversion/Verk/Språk (se ovan under Översättning). Länka till entiteten för språket som resursen delvis är en översättning från.  
 
##### Sammanfattningsspråk  
Se Sammanfattning av innehåll   
  
##### Språkanmärkning     
* Anmärkning/Anmärkning om språk/Anmärkning: Språk/Benämning (hasNote/marc:LanguageNote/marc:LanguageNote/label = 546 ‡a)  
  ```Exempel: Parallelltext på svenska och engelska```  
  Anmärkningen är under arbete och fungerar tyvärr ännu inte.  
  
#### Genre  
 Länka till entitet. 
För att söka efter entiteter inom Genre/form, klicka på plustecknet vid Genre/form (lägg till entitet). I Lägg till entitet (längst upp i sidorutan till höger), välj typ i listan över typer. Skriv in sökbegrepp. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj entitet genom att klicka på plustecknet vid entiteten (Lägg till). Vid behov, välj ytterligare entiteter i listan. Om sidorutan är stängd, klicka på plustecknet vid Genre/form (lägg till entitet) för att söka fram och välja fler entiteter.  

##### Saogf-termer  
* Genre/form – saogf-termer (genreForm = 655 -/7 ‡a, ‡2 saogf)  
 Välj Genre/form i listan över typer. Avgränsa till saogf-termer genom att skriva "saogf" efter söktermen. Länka till entitet.  
 Träfflistan vid sökning på entiteter är för närvarande inte sorterad. Var därför uppmärksam på att det finns liknande genre/form-termer med olika listkoder, till exempel sao, barngf, gmgpc/swe. Välj kod från rätt lista. Mer [information om listkoder](http://www.kb.se/katalogisering/Svenska-amnesord/genrer-form/).  
 ```Exempel: Självbiografier```  
  Se [instruktionsfilm](https://www.youtube.com/watch?v=wrqs310Nt0M&list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy&index=7)  
  
##### Litterär genre  
* Genre/form – litterär genre (genreForm = 008/33)  
  Välj Litterär genre i listan över typer. Länka till entitet.  
  ```Exempel: 0 ( = ej skönlitterärt verk)```
  
##### Biografiskt material  
* Genre/form – biografiskt material (genreForm = 008/34)  
  Välj Biografiskt material i listan över typer. Länka till entitet.  
  ```Exempel: a (= självbiografi)```  
    
##### Festskrift     
* Genre/form – festskrift (genreForm = 008/30)  
  Välj Festskrift i listan över typer. Länka till entitet.    
  ```Exempel: Ja, resursen är en festskrift```    
    
##### Konferenspublikation       
* Genre/form – konferenspublikation (genreForm = 008/29)  
  Välj Konferenspublikation i listan över typer. Länka till entitet.         
  ```Exempel: Ja, resursen härrör från konferens```   
     
##### Akademisk avhandling      
* Genre/form – akademisk avhandling (genreForm = 008/24-27)  
  Välj Innehåll 1, Innehåll 3, Innehåll 2, i listan över typer. Skriv "avhandling" i sökrutan. Länka till entitet.      
  ```Exempel: Akademisk avhandling```  

#### Klassifikation  
* DDK-klassifikation  
  För att lägga till DDK-klassifikation:  
  * Om posten har Klassifikation/Klassifikation (till exempel SAB-klassifikation) men saknar Klassifikation/DDK-klassifikation, lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till klassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj DDK-klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till egenskaper under: Text). Välj Klassifikation. Klicka på plustecknet vid Klassifikation (Lägg till klassifikation).  Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj DDK-klassifikation.  
   Skriv in uppgiften under Kod.  

* Klassifikation/DDK-klassifikation/Kod (classification/ClassificationDdc/code = 082 0/4 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 327.12092```
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga (classification/ClassificationDdc/edition = 082 ‡2)  
  ```Exempel: full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift (classification/ClassificationDdc/editionEnumeration = 082 ‡2)  
  ```Exempel: 23/swe```  
  
##### Sekundär DDK-klassifikation  
Lägg till DDK-klassifikation (sekundär) genom att klicka på plusikonen vid Instans av Verk/Text (Lägg till egenskaper under: Text) och välja DDK-klassifikation (sekundär).  
Klicka sedan på plustecknet vid DDK-klassifikation (sekundär) (Lägg till ddk-klassifikation) och välj Skapa lokal entitet (längst ner i sidorutan till höger). Skriv in uppgiften under Kod.  
* Klassifikation/DDK-klassifikation/Kod (additionalClassificationDdc/ClassificationDdc/code = 083 0/- ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 791.430233092```
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga  
  (classification/ClassificationDdc/edition = 083 ‡2)  
  ```Exempel: full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift  
 (classification/ClassificationDdc/editionEnumeration = 083 ‡2)  
  ```Exempel: 23/swe``` 
   
##### SAB-klassifikation  
* SAB-klassifikation  
  För att lägga till annan klassifikation, till exempel SAB-klassifikation:  
  * Om posten har Klassifikation/DDK-klassifikation men saknar Klassifikation/Klassifikation (till exempel SAB-klassifikation), lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till klassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj Klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till egenskaper under: Text). Välj Klassifikation. Klicka på plustecknet vid Klassifikation (Lägg till klassifikation).  Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj Klassifikation.  
   Skriv in uppgiften under Kod.   
* Klassifikation/Klassifikation/Kod (classification/Classification/code = 084 0/4 ‡a)  
     Skriv in uppgiften.  
  ```Exempel: Sei-e```   
* Klassifikation/Termlista/Termlista/Kod (classification/Classification/inScheme/ConceptScheme/code = 084 ‡2)  
 ```Exempel: kssb```  
* Klassifikation/Termlista/Termlista/Version (classification/Classification/inScheme/ConceptScheme/version = 084 ‡2)  
 ```Exempel: 8``` 
 
#### Amne  
* Ämne  
  Länka  i första hand till entiteter för ämnesord. Följ instruktionerna på följande sidor:  
  [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)   
  [Lägg till sammansatt men ej auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-non-auth-sh)   
  [Lägg till kontrollerade men ej auktoriserade ämnesord](https://libris.kb.se/katalogisering/help/workflow-controlled-non-auth-sh)   
  [Lägg till okontrollerade ämnesord, t.ex. prel-termer i samband med ämnesordsförslag](https://libris.kb.se/katalogisering/help/workflow-uncontrolled-sh)

##### Allmänt ämnesord  
* Ämne - sao-term  (subject = 650 -/7 ‡a, ‡2 sao)  
  Länka till entitet från Svenska ämnesord, enligt instruktion: 
  [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)    
   
* Ämne - annan kontrollerad lista (subject = 650 -/7 ‡a, ‡2)  
  För ämnesord från andra kontrollerade listor, följ denna instruktion:  
  [Lägg till kontrollerade men ej auktoriserade ämnesord](https://libris.kb.se/katalogisering/help/workflow-controlled-non-auth-sh)  
  
* Ämne - okontrollerade (subject = 653 -/- ‡a)  
  För ämnesord från andra kontrollerade listor, följ denna instruktion:  
  [Lägg till kontrollerade men ej auktoriserade ämnesord](https://libris.kb.se/katalogisering/help/workflow-controlled-non-auth-sh)   

##### Allmänt ämnesord med underindelning   
* Ämne - sao-term  (subject = 650 -/7 ‡a, ‡x, ‡2 sao)  
  Länka till entitet från Svenska ämnesord, enligt instruktion: 
  [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)  
  
  
##### Geografiska ämnesord  
* Geografiskt ämnesord (subject = 651 -/4 ‡a)  
  
  
##### Geografiskt ämnesord med geografisk underindelning  
* Geografiskt ämnesord (subject = 651 -/7 ‡a, ‡x, ‡2 sao)  
  För auktoriserade geografiska ämnesordssträngar, följ denna instruktion:    
 [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)   
  För ej auktoriserade geografiska ämnesordssträngar, följ denna instruktion:  
 [Lägg till sammansatt men ej auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-non-auth-sh) 
   
##### Kronologiskt ämnesord
* Ämne/Kronologiskt ämnesord (subject = 648 7/- ‡a, ‡2 sao)  
  Länka till entitet. Följ denna instruktion:    
  [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)   
  
##### Ämnesord Person  
* Ämne/Agent/Person (subject = 600 1/4- ‡a)      
 Länka till entitet. Följ dessa instruktioner:  
 [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)   
 Vid behov, skapa ny agent, enligt instruktion:  
 [Skapa ny agent - person](https://libris.kb.se/katalogisering/help/workflow-agent-person-new) eller  
 [Redigera befintlig agent - person](https://libris.kb.se/katalogisering/help/workflow-agent-person-edit)  
 I undantagsfall, skapa lokal entitet.  
  
##### Ämnesord Organisation  
* Ämne/Agent/Organisation (subject/agent/Organization = 610 2/- ‡a)  
  Länka till entitet. Följ dessa instruktioner:  
  [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)   
  Vid behov, skapa ny agent, enligt instruktion:  
  [Skapa ny agent - organisation](https://libris.kb.se/katalogisering/help/workflow-agent-organisation-new) eller  
  [Redigera befintlig agent - organisation](https://libris.kb.se/katalogisering/help/workflow-agent-organisation-edit)  
  I undantagsfall, skapa lokal entitet.  
 
#### Malgrupp     
 * Målgrupp (intendedAudience = 008/22)  
  Länka till entitet.  
  Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.    
  ```Exempel: j (= barn- och ungdom, 0-16 år)```  
  
#### Innehallstyp
* Innehållstyp/Innehållstyp (contentType/ContentType = 336 ‡b)   
  Länka till entitet.  
  ```Exempel: text (txt)```  
  För att lägga till ytterligare innehållstyp, till exempel "sti" = stillbild för en bilderbok med både text och bild, lägg till Har del under Instans av Verk, från plustecknet vid Text (Lägg till egenskaper under: Text). Skapa därefter Verk som lokal entitet genom att klicka på plustecknet vid Har del (Lägg till resurs). Välj Skapa lokal entitet och välj därefter ++ Verk i listan. Lägg därefter till Innehållstyp från plustecknet vid Verk (Lägg till egenskaper under: Verk). Sök fram och länka till entitet.  
  EXEMPEL PÅ OLIKA INNEHÅLLSTYPER HÄNVISA TILL FORMATHANDBOKEN  
  
#### Sammanfattning av innehall    
 * Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 ‡a)  
För att lägga till Sammanfattning av innehåll, klicka på plustecknet vid Instans av Verk/Text - Lägg till egenskaper under: Text. Välj Sammanfattning av innehåll. Tryck Enter för att lägga till Samanfattning. Tryck Enter för att söka fram och lägga till Benämning (Lägg till egenskaper under: Sammanfattning).  
 Skriv in uppgiften under Benämning.  
  ```Exempel: Åtskilliga utdrag af framledne … Axel v. Fersens bref till f.d. konungen av Swerige, Gustaf Adolph, 1806```  
  
 * Typ av innehållsbeskrivning/sammanfattning (marc:summaryType = 520 ind1)  
 Sök fram och lägg till Typ av innehållsbeskrivning/sammanfattning (plustecknet vid Sammanfattning - lägg till egenskaper under: Sammanfattning). Välj typ från lista.  
 ```Exempel: Ej preciserad``` 
 
##### Sammanfattningsspråk  
* Sammanfattning av innehåll/Sammanfattning/Språk (summary/Summary/language = 041 ‡b)  
För att lägga till sammanfattningsspråk, klicka på plustecknet vid Instans av Verk/Text (lägg till egenskaper under: Text) och välj Sammanfattning av innehåll. Lägg till Sammanfattning (tryck Enter eller klicka på plustecknet vid Sammanfattning av innehåll - Lägg till Sammanfattning). Ta bort Benämning. Lägg till Språk genom att klicka på plustecknet vid Sammanfattning (Lägg till egenskaper under: Sammanfattning) och välj Språk. Sök fram och länka till entiteten för sammanfattningens språk.  
  ```Exempel: Engelska```