1. Öppna din dators terminal och navigera till den mappen du vill ha repot inuti

2. när du hittat ditt du vill ha den använd dig av git clone <länken till repot> så kommer github repot klonas till din maskin så du kan öppna filerna.

3. Skriv sedan code . medans du är inuti repot. Så kommer visual code öppnas automatisk så du kan kolla på alla filer som finns i repot

4. Ladda ner live server extensionen för att kunna visa hur filerna hade sett ut som en hemsida.

5. I hemsidan har du index.html som är "home" där första innehållet visas. I headern finns en knapp som leder till en undersida som heter timeline(timeline-html) Där kan du visa det sekundära innehållet.

6. Båda huvudsidan och undersidan är helt navigerbara med hjälp av tabindex.


Projektkrav:

1. HTML-struktur
Jag har använt mig av header, nav, main, section, article, footer.
Jag har inte använt mig av div någonstans i något av dokumentet

2. CSS-styling

header, header nav är designad med flex, artist rekomendation är designad med flex. subgenre-article är designad med flex

main är gjord med grid layout med varierande mängd kolumner och rows.
Section i main är designad med grid så kunde placera children olika med hjälp av media queries.

Classer och id har jag namnget för att beskriva vilket element dem har och i vilken "container" som: 
main-index(main i index fil)--->main-section(Section inuti i main)----->section-article(Sections artiklar).
Jag har osså använt beskrivande classer som subgenre-section(Section som innehåller articlar med subgenrer)

Jag har designat mobile first och har två queries för Tablets:          (600-912)
Computers:        (min-912)

3. Responsiv design
Layouten är fullt responsiv för mobila, tablet och dator enheter.
Clamp har änvänts för font size och dimensionerna för sungenre artiklarna.


4. Tillgänglighet
alla bilder har alt atribut

Länkarna har beskrivande aria atribut

Rubrikerna följer en tydlig struktur

en tabindex Hjälper dig naviger hela hemsidan.

Färgkontrasten Har ja korrigerat med WAVE

5. Webbläsarverktyg
Med Webbläsarverktyg har jag under produktionen använt för att se så layouten agerar så som jag vill och dem ändraingarna jag gjort, har ändrats enligt min vision.

Responsiviteten har jag testat med webbläsarvertkyg under processen med hjälp av webbläsarvertkyg.

Med WAVE har ja kollat efter errors, contrast errors, och alerts.

Dem enda alerts som nu dyker upp är positive tab index, som finns för att main innehållet på timeline ska tabas igenom efter behag.
Redundant alternative text på bilderna, som kvarstår för dem är relevanta


6. Versionshantering med Git
Jag har arbetat på varsin sida på varsin branch för att sedan merga dem till master för att göra en code review och sedan deploya hemsidan.
