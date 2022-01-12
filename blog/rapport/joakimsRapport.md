HTML_CSS_projektarbete - Johan, Jon, Jahirul, Joakim

Delar som skall vara med. - Joakim har blog. 

- [Hemsidan:](#hemsidan)
  - [Bootstrap](#bootstrap)
  - [Figma](#figma)
  - [HTTP](#http)

Grupprojekt - Skapa en webbplats

> Täckta kursplansmål:
>
> 1. Beskriva och förklara delar av HTML, semantisk HTML, CSS och dess syntax
> 2. Redogöra för hur webbläsare kommunicerar via HTTP samt URL:ers uppbyggnad
> 3. Ge enklare exempel på sökmotoroptimering
> 4. Använda aktuella CSS ramverk för layout och positionering samt Bootstrap för att skapa responsiva sidor.
> 5. Tillämpa HTML-strukturer för att bättre påverka sökoptimering.
> 6. Motivera valda lösningar för en webbsidas uppbyggnad och struktur.
> 7. Använda och ta fram wireframes som underlag för en webbsida.
> 8. Självständigt producera ett gränssnitt med korrekt användning av HTML och CSS, bootstraps samt wireframes

Uppgift

5. En sida som innehåller en blogg där någon skriver relevanta inlägg för företaget eller organisationen. Sidan ska innehålla en övergripande vy med minst tre blogginlägg, som är avkortade på något sätt. Det ska sedan gå att fälla ut hela blogginlägget genom att klicka. Det finns en bloggnavigering som länkar till de olika blogginläggen på sidan.

Att vara ansvarig för en del betyder inte att man är den enda personen som skriver den biten utav sidan, utan man ansvarar för att den blir skriven. Alla sidor måste inte göras utan det beror på storleken på gruppen.

G krav:

Det är väldigt viktigt att alla committar tidigt och ofta. Committa varje dag du sitter och jobbar och committa så fort du löst något problem i ditt arbete. Om jag inte har commits så har jag inget betygsunderlag att godkänna på. **Commits är alltså lika viktigt som själva arbetet.** Saknas commits så får man skriva om arbetet.

  # Hemsidan:

  - Har sett till att hemsidan är responsiv (desktop+smartphone) (Mål 4)
  
  Har gjort genom kod och media query.

  - Det ska finnas en gemensam styling som alla sidor använder. Man kan ha unika stylings per sida utöver detta. (Mål 4 & 1)

  Vi har en gemensam styling med ett återkommande tema i vår egen desing. 

  - Webbplatsen ska vara sökmotorsoptimerad (semantisk HTML mm.), och ni ska tillsammans i gruppen välja och jobba med 2 till 3 nyckelord på varje sida. (Mål 5 & 2)

  Har inte gjort detta ännu! 

  - Minst en Bootstrap snippet eller komponent testat per person (Mål 8)
  ## Bootstrap

  Bootstrap finns med.

- Rapporten:

  - Ha med Wireframen du använde för ditt ansvarsområde (png/bmp/jpg/pdf) (Mål 7)

  ## Figma

  Bilden visar både en desktop och hur den ser ut på en mobil. 

  ![rapportFigma](https://user-images.githubusercontent.com/89445183/148766267-be89cdc5-d7aa-4bd6-b020-a0d5b84d0c0e.png)

  - Skriv vilka nyckelord ni valde och vad du gjort för SEO på ditt ansvarsområde. (Mål 6)

  Detta och sökmotorsoptimerad är ej hjord.

  - Använd bilder från Inspector verktyget och förklara i grova lag hur webläsaren använder HTTP för att besöka just din hemsida. (Mål 2)

  ## HTTP

  Om jag använder Developer tools, väljer fliken Network och slår enter så körs sidan om och vi får lite information. Se bild. 

   ![http](https://user-images.githubusercontent.com/89445183/148769324-76e0049b-7396-4ac2-a94a-4b63508c59c9.png)

  I bilden ovan beskrivs ett flöde av information som hämtas, dessa adresser är http (HyperText Transfer Protocol) som innehåller iformation. Detta sker upprepade gånger enligt listan under namn. Varje moment går på några få millisekunder. 

  Den hade börjat på index.html och här finns information till sidan om vad den skall göra sedan, vad som skall begäras in. 

  Varje bit som hämtas använder sig av metoden GET. Om detta går som de skall så får vi tillbaka en statuskod 200. Detta betyder att vår begäran fungerat som den skall. 
  Detta upprepas då på allt som just denna sidan innehåller, och i mitt fall hade nästa steg varit boostrap.min.css. 

  Information som kan finnas på en index sida i sin head kan beskriva t ex om vi behöver hämta en link för en bild, css, js osv. 

  





  - Förklara varför just den URL som används i HTTP anropet ovan används. _(Använd ord som: schema/protokoll, auktoritet/server/domän, sökväg/resurs)_ (Mål 2)

  - Självständigt reflektera över och kritiskt granska de valda lösningarna i projektet gällande design och wireframes, HTML, CSS, samt Bootstrap.

VG krav:

- Hemsidan:
  - Använt flera bootstrap components/snippets och även customizat styling, inom eget ansvarsområde (Mål 8)

Varning om copy-paste

Om jag ser copypaste kod som är nästintil oförändrad så kan jag inte godkänna om studenten har tagit till sig hur koden fungerar. Efter copypaste så måste man forma om HTML och CSS koden så att den passar in i hemsidan och sen committa.

Tänk på att fråga innan ni hämtar kod av varandra i en projektgrupp med. Passa på om att fråga hur koden fungerar och hur du ska tänka när du får den att fungera i din hemsida.

Inlämning

1. En i gruppen forkar inlämningsrepon i början. Alla andra sammarbetar sen på forken.

2. I slutet, gör PR till upstream.

3. Skicka in på PingPong Gruppprojekt:

   - Varje person lämnar in en zip av repon med all versionshistorik
   - Länkar till projektet på GitHub

4. Skicka in på PingPong Rapport:
   - Varje person lämnar in sin egna rapport (pdf, eller zip med md och tillhörande bildlänkar)
   - Länkar till rapporten på GitHub
