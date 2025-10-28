OPPGAVE:

Dere skal samarbeide i grupper på 2 om å lage en one-page nettside med en av planetene i solsystemet som tema.

Nettsiden skal ha en ganske enkel struktur: Header med en navbar som scroller til de forskjellige seksjonene. Minimum 2 seksjoner.  Forslag til seksjoner: Bildegalleri, Infoside, Faktaliste etc. Se layout mal nederst.

Fokus skal være på design og layout, valg av fargetema, valg av bilder, valg av fonter.

TIPS: 

//HTML

<section id="mysection"></section> // container element for section
<a href="#mysection"></a> // link til navbar knappene som scroller til section
//CSS

html { 
scroll-behavior: smooth; 
}
/* Med denne får du en smooth scroll når du navigerer til section */

Dere skal planlegge design og layout i Figma. (En lager figma prosjektet og inviterer den andre til å være editor i prosjektet). Figma skissen kan enten være kun wireframe og konsept, eller full skisse (Men husk å sette av god tid til å kode ut siden!)
Siden skal kodes med HTML og CSS. Det legges vekt på god bruk av semantisk og ryddig HTML og bruk av flex-box til layout i CSS (I CSS skal du være varsom med bruk av position absolute og absolutte verdier. Spør om du er usikker på hva som menes med dette.)
Siden trenger ikke å være responsiv (dvs den trenger ikke å optimaliseres for mobil)
Dere skal samarbeide om koding med å bruke 1 GitHub repository som begge pusher og puller kode til/fra  (en lager repository og gir den andre tilgang. Dette kan vi hjelpe med.)
Husk å kommentere i koden.
Siden skal hostes på GitHub Pages (gratis hosting tjeneste, her er en quickstart guide: https://docs.github.com/en/pages/quickstartLinks to an external site.)
LYKKE TIL! 😊

Ressurser
https://unsplash.com/Links to an external site. og https://www.pexels.com/Links to an external site. er gode ressurser for lisensfrie bilder.

https://solarsystem.nasa.gov/planets/overview/Links to an external site. er en bra ressurs for bilder/informasjon.

---

MINE NOTATER:

PROSJEKT JUPITER (hvordan nettsiden vil være delt opp):

Header: logo | Jupiter, Måner, Utforskning

-

seksjon 1: Hero: fullskjerms bilde av Jupiter og tekst som sier "Jupiter: Solsystemet's hersker?"

seksjon 2: tittel: "Fakta om Gasskjempen"

seksjon 3: fire kort: "Størrelse", "sammensetning", "den røde flekken", "Hurtig rotasjon og stormer."

-

seksjon 4: emneskille med et stort bilde: Jupiters fire galileiske måner som gir en introduksjon til månene og de fire galileiske månene. (identisk til seksjon 1 med samme css)

seksjon 5: tittel: "De fire galaktiske månene" (identisk til seksjon 2 med samme css)

seksjon 6: fire kort: Io, Europa, Ganymedes, Callisto. (identisk til seksjon 3 med samme css)

-

seksjon 7: James Webb bilde 

Seksjon 8: Utforskning og oppdagelser

seksjon 9: 4 forskjellige utforskede elementer: "Søket etter Liv i Europas Skjulte Hav", "James Webb-teleskopet: Jupiters Nordlys og Jetstrømmer", "Stormen Som Ikke Vil Dø", "Hvordan Jupiter Fungerer som et Skjold"

-

Footer:
Venstre: Logo + (navn), epost: ProsjektJupiter@gmail.com, lokasjon: NASA (florida),
Høyre: kilder: link til forskjellige nettsider som informerer (Wikipedia), snl etc.

-

Nettsiden er bygd opp med en header og 3 css filer som repeteres 3 ganger: image, title, card repeat. (Samme css filene brukes for å lage seksjon 1, 2 og 3 som 4, 5, 6 og 7, 8, 9.), til slutt en footer.

-

Farger som passer til nettsiden i stil med Jupiter som legges i root:
Mørke farger: svart og mørk grå med blåtoner/ lilla toner
Kontrast/accent farger: rød/oransje, lys grå.
#0A041C, #1F1538, #FCEFD5, #70A0CC, #C95F38, #991f00
font: Poppins

Alle notatet er skrevet før jeg har begynt på index.html, og filstrukturen ser allerede slik ut uten noe kode, før jeg har startet på prosjektet:

![alt text](image.png)

---
