---
section: Sök
title: Utforma sökfrågor
order: 1
date: 2019-02-21
tags:
- search
---

# Sök

## Operatorer för frågespråk

   `+` betyder AND  
   `|` betyder OR  
   `-` innebär uteslutning  
   `"` används för frassökning  
   `*` innebär trunkering av en term  

---

### Standardsökning

En standardsökning ger träff på sammanslagen sökterm. En sökning på Astrid Lindgren kommer matcha poster som innehåller Astrid och Lindgren, oavsett ordning och oavsett var i posten orden finns. Sökningen kommer alltså även matcha `Lindgren Astrid`, `Astrid heter i efternamn Lindgren` och liknande.

### Exakt sökning

Om du vill söka på en exakt fras, använd `"`. En sökning på `"Emil i Lönneberga"` ger träff på fras i angiven ordning. Sökningen kommer alltså inte matcha till exempel `Emil som bor i Lönneberga`.

### Eller

Om du vill söka på eller, använd `"|"`. Exempelvis ger `"Tove Jansson" | "Astrid Lindgren"` träff på `Tove Jansson` eller `Astrid Lindgren`.

### Utesluta termer

Om du vill utesluta en term, använd `-`. Exempelvis ger `Astrid -Lindgren` alla träffar som innehåller `Astrid` men inte `Lindgren`.

### Gruppering av termer 

Om du vill gruppera termer och operatorer, använd `(` och `)`. Exempelvis ger en sökning på `(Tove | Lars) Jansson`träff på Tove eller Lars Jansson. Utan parenteserna söker du efter `Tove` eller `Lars Jansson`, men med parenteserna söker du på `Tove Jansson` eller `Lars Jansson`

### Trunkering

Om du vill trunkera, använd `*`. Trunkering ger träff på alla ändelser efter prefixet. Exempelvis ger `sol*` träff på bland andra `solros` , `sola` och `solig`.  

### Avgränsa sökningen

Det går att avgränsa sökningen till ISBN, ISSN eller titel. Välj alternativ i menyn vid sökrutan. Om man inte väljer någon avgränsning söker man som fritext. 

### ISBN

I nya Libris sparas ISBN utan bindestreck.  

För att söka på ISBN i fritextsökning (utan avgränsning), ta bort bindestrecken.  

    Exempel fritextsökning: `9789144113074`

För att söka på ISBN med eller utan bindestreck, välj att söka med  avgränsning ISBN.  

    Exempel ISBN: `9789144113074`
    Exempel ISBN: `978-91-44-11307-4`

För att söka på ogiltiga ISBN eller ISBN som hör till annan version (Indirekt identifierad av), sök ISBN som fritext, utan bindestreck.  

### Sökning på specialtecken

I Libris lagras all text i [Unicode - UTF-8]( https://sv.wikipedia.org/wiki/UTF-8), den teckenkod som tillåter hantering av världens alla språk. Det finns trots det vissa problem med hantering av diakriter och andra specialtecken. Arbete med normalisering av tecken pågår. För att ändå få träff vid sökning där diakriter och specialtecken ingår, följ denna instruktion.

Vissa tecken kan vara kodade på olika sätt, prekomponerade (sammansatta) eller dekomponerade. Prekomponerade tecken innebär att grundbokstav och sammanhörande diakrit uppträder som ett sammanhållet tecken. Dekomponerade innebär att grundbokstav och sammanhörande diakrit uppträder som separata tecken.

1. Kopiera och klistra in sträng.
2. Om det finns prekomponerade (sammansatta) tecken i strängen, ersätt tecknet med grundbokstaven.
2. Om det finns dekomponerade tecken i strängen, ställ textmarkören efter ett sådant och tryck backsteg en gång. Detta ska resultera i att t.ex. "bokstav + diakrit" ändras till "bokstav". Om det blir två tecken vid inklistring (eller bara frågetecken), ta bort de "konstiga" bitarna.
4. Skriv in en tilde, "~", efter varje ord där ersättning har gjorts.
5. Sök.