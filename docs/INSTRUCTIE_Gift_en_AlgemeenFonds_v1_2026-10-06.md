# Instructie: de gift aan Stichting Naberschap en het AlgemeenFonds

**Versie 1 · 6 oktober 2026 · voor de bouw van naberschap.nl (concept 0.3 en later)**
Status: concept, niet vastgesteld door een bestuur. Naberschap is in oprichting en er is nog geen AlgemeenFonds. Bij strijd gaat de Stelselnotitie voor. Geen fiscaal of juridisch advies.

Bronnen: Notitie AlgemeenFonds Naberschap v1 (29-09-2026), Fonds op Naam uitleg A4 v2 (29-09-2026), Projectinstructie Website v1.1, Huisstijl Naberschap (concept 6-10-2026), Stelselnotitie (hoogste versie in het Project).

## 0. Aansluiting op de huidige giftpagina (commit "Doneren: drie routes")

De knop heet nu "Doneren" en opent een pagina "Doneren aan Stichting Naberschap" met drie routes: Directe gift, Fonds op Naam en Nalatenschap. Houd die opzet. Route 1 is de gift aan de stichting zelf en is de plek voor het AlgemeenFonds. Pas dit aan:

1. **Route 1, Directe gift.** Vervang de tekst door: "Je geeft rechtstreeks aan Stichting Naberschap. Zonder bestemming komt je gift in het AlgemeenFonds. Het bestuur beslist zelfstandig waar het naartoe gaat. Je mag een voorkeur voor een aandachtsgebied doorgeven. Dat is een advies. Je gift gaat niet naar Mondéall BV." Voeg onder de kaart de kostenzin uit §8 toe. Het formulier uit §4 (bedrag leeg, keuze algemeen of aandachtsgebied, eenmalig) hoort achter deze route. Tot de oprichting blijft de betaalknop uitgeschakeld.
2. **Route 2, Fonds op Naam.** De zin "Draag bij aan een bestaand Fonds op Naam" moet weg: dat is niet vastgelegd (zie §6 en open punt 7). Schrijf: "Begin je eigen fonds onder een naam die jij kiest. Een fonds start met een fondsovereenkomst, niet met een betaalscherm."
3. **Kop van de pagina.** De regel "Stichting Naberschap is een ANBI (in aanvraag)" moet weg. De ANBI-status moet nog worden aangevraagd en er mag geen ANBI-claim op de site staan. Schrijf: "Stichting Naberschap is in oprichting. De ANBI-status is nog niet toegekend."
4. **Label.** "Doneren" op de knop en de pagina: zie §4 en open punt 5.
5. **Nalatenschap (route 3).** Een nalatenschap zonder bestemming valt ook in het AlgemeenFonds (Notitie AlgemeenFonds §3). De bestaande tekst is veilig en kan blijven, met de zin "Informatie over nalatenschap volgt na oprichting".

## 1. Wat je moet bouwen, in één alinea

De knop rechtsboven in de kop leidt naar één giftscherm voor een **gift aan Stichting Naberschap zelf**. Zo'n gift is standaard **ongeoormerkt** en komt in het **AlgemeenFonds** terecht: het deel van het vermogen waarover het bestuur zelfstandig beslist. De gever kan een **voorkeur voor een aandachtsgebied** uitspreken, nooit voor een project, een club of een persoon. Wie wil dat zijn geld blijvend werkt, of onder een eigen naam, begint geen gift maar een **Fonds op Naam**. Die twee routes blijven op de site uit elkaar.

## 2. Het verschil dat de bezoeker moet snappen

| | Gift aan Stichting Naberschap | Fonds op Naam |
|---|---|---|
| Waar komt het terecht | AlgemeenFonds, niet geoormerkt | Een eigen fonds onder een naam die de gever kiest |
| Blijvend? | Nee. Het AlgemeenFonds is een bestedingsfonds en kan niet uit zichzelf een blijvend fonds worden | Kan blijvend (instandhouding) of met looptijd |
| Wie beslist over de besteding | Het bestuur | Het bestuur, met advies van de gever |
| Wat kan de gever kiezen | Een voorkeur voor een aandachtsgebied | Naam, aandachtsgebied en vorm |
| Hoe begint het | Via het giftscherm | Met een fondsovereenkomst, niet met een betaalscherm |

Eén zin voor in de interface, onder de knop: *"Wil je dat je geld blijvend werkt, of onder je eigen naam? Dan is een Fonds op Naam passender."*

## 3. Wat er na een gift gebeurt (de waarheid, niet meer en niet minder)

Zeg dit op het giftscherm of er direct naast, in B1:

1. Je gift gaat naar Stichting Naberschap (in oprichting). Niet naar Mondéall BV.
2. Zonder bestemming komt je gift in het AlgemeenFonds. Het bestuur beslist waar het naartoe gaat.
3. Je mag een voorkeur voor een aandachtsgebied doorgeven. Dat is een advies. Het bestuur hoeft het niet te volgen en kiest zelf de projecten.
4. Het bestuur wil ongeoormerkte giften binnen een redelijke termijn besteden en legt per toekenning vast wat, waarvoor en waarom.
5. Een deel van ongeoormerkte giften kan nodig zijn voor de kosten van Naberschap zelf, bijvoorbeeld voor de accountant en de administratie. Naberschap maakt jaarlijks zichtbaar hoe de kosten zich verhouden tot wat er is besteed.

Let op bij punt 4 en 5: dit zijn voorgenomen uitgangspunten uit het concept-Beleidsplan en de Notitie AlgemeenFonds, geen vastgesteld beleid. Schrijf "wil" en "streeft naar", niet "doet" en "garandeert". Gebruik nooit het woord "100%" voor Naberschap. Dat honderd-procentbeginsel hoort bij het Mondéall-platform en geldt niet voor de kosten van de stichting.

## 4. Het giftscherm (component Giftscherm)

Alles in Naberschap-stijl: woordmerk, kobalt, vermiljoen, bolletje. Geen Mondéall-elementen, geen klavertje.

**Velden, in deze volgorde:**
1. **Bedrag in euro.** Leeg. Geen voorgeselecteerd bedrag, geen voorgestelde bedragen met een "populair"-label.
2. **Waar wil je dat het heen gaat?** Twee keuzes (radio):
   - *Naberschap in het algemeen* (AlgemeenFonds). Dit is de standaard.
   - *Met een voorkeur voor een aandachtsgebied*, met daaronder een keuzelijst. Neem de gebieden uit de Kwalificatietabel ANBI-aandachtsgebieden (v3, 29-09-2026) over, niet uit je hoofd. De A4 noemt als voorbeelden armoedebestrijding, natuur en milieu, cultureel erfgoed en basisonderwijs.
3. **Eenmalig of periodiek.** In fase 1 en 2 alleen *eenmalig*. Periodiek (minimaal vijf jaar, schriftelijke overeenkomst) komt pas na toekenning van de ANBI-status en na toetsing door een belastingadviseur. Tot dan staat er "Periodiek geven volgt na toekenning van de ANBI-status." Zet er geen aftrekclaim bij.
4. **Ontvanger als gewone tekst direct bij de knop:** "Je geeft aan Stichting Naberschap (in oprichting)."
5. **E-mailadres** alleen als er een bevestiging nodig is, met één doel erbij. Geen account, geen nieuwsbrief als vooringevuld vinkje.

**Knoptekst:** "Gift aan Stichting Naberschap" of "Geef aan Stichting Naberschap". Niet "Doneren". De Projectinstructie verbiedt doneren en donateur (gift, niet schenking, niet doneren). Mathieu noemt de knop zelf "doneren aan stichting naberschap"; dit is een bewuste afwijking om te bevestigen.

**Niet doen:** vooraf ingevulde bedragen, tellers, voortgangsbalken, urgentie ("nog 2 dagen"), schuldgevoel, dankbaarheid als tegenprestatie, zichtbaarheid of logo's voor gevers of bedrijven.

## 5. Waar de knop staat en wat hij doet per fase

| Fase | Gedrag van de knop |
|---|---|
| 1. Nu, concept en noindex | Knop zichtbaar, giftscherm als voorbeeld, betaalknop uitgeschakeld ("Betalen volgt na oprichting"). Niets wordt verstuurd of betaald. |
| 2. Na oprichting, eigen bankrekening en betaalrelatie op naam van de stichting | Betaalknop live. Teksten eerst getoetst door belastingadviseur en notaris. |
| 3. Na toekenning ANBI-status | ANBI-vermelding en periodieke gift mogen verschijnen. Over aftrek pas iets zeggen nadat een belastingadviseur de tekst heeft getoetst, feitelijk en zonder belofte. |

Locaties van de knop: rechtsboven in de kop op elke pagina (staat er al), en onderaan de pagina Over Naberschap. Niet bij "Kies je eerste stap" op de voorpagina (besluit van Mathieu, 6 oktober).

## 6. De voorbeeldfondsen en de gift (belangrijke correctie op concept 0.3)

In concept 0.3 kan een bezoeker op het giftscherm een fictief voorbeeldfonds kiezen, en staat op elke voorbeeldpagina "Draag bij aan dit fonds". De bronnen ondersteunen dat niet: de A4 kent bij Naberschap een gewone gift met een voorkeur voor een aandachtsgebied, en een Fonds op Naam start met een fondsovereenkomst. Een gift van een derde aan een bestaand fonds van een ander is nergens vastgelegd.

Pas dit zo aan, zodat de wens van Mathieu (een donatieknop bij elk voorbeeld) blijft staan:

- Haal de voorbeeldfondsen uit de keuzelijst op het giftscherm.
- Laat de knop op een voorbeeldpagina openen met het aandachtsgebied van dat fonds als **voorkeur** (bijvoorbeeld Natuur en milieu bij Fonds Eikenlaan).
- Knoptekst op de voorbeeldpagina: "Geef aan Stichting Naberschap, met voorkeur voor Natuur en milieu".
- Tekst erbij: "Dit is een gift aan Stichting Naberschap met een voorkeur voor het aandachtsgebied. Het is geen bijdrage aan dit voorbeeldfonds. Wil je zelf zo'n fonds, dan begin je een eigen Fonds op Naam."
- Zet de knop "Begin je eigen Fonds op Naam" boven de giftknop.

## 7. Wat nooit op de site mag

- Geen suggestie dat de gift via Mondéall BV of het platform naar Naberschap loopt, en geen gift met "Manier 1" (direct geven via Naberschap als platform-Initiatief). Dat is vervallen in Stelselnotitie §7.
- Geen sponsorgeld, geen tegenprestaties en geen Sponsors van de BV. Een bedrijf mag zonder tegenprestatie aan Naberschap geven, maar krijgt daarvoor geen zichtbaarheid.
- Geen bijdrage van Mathieu of Mondéall BV als startgift (Notitie AlgemeenFonds §6). Daarover geen tekst op de site.
- Geen toezegging dat een voorkeur wordt gevolgd, geen "jij bepaalt", geen "wij voeren je wens uit".
- Geen claim over ANBI, aftrek, bedragen of kostenpercentages die niet vaststaan. Nergens het woord "garantie".
- Het AlgemeenFonds wordt nergens "blijvend" of "stamvermogen" genoemd.

## 8. Teksten (voorstel, B1, jij/je)

**Kop giftscherm:** Geef aan Stichting Naberschap.

**Intro:** Je gift gaat rechtstreeks naar Stichting Naberschap en niet naar Mondéall BV. Zonder bestemming komt hij in het AlgemeenFonds. Het bestuur beslist zelfstandig waar het geld naartoe gaat.

**Uitleg onder "voorkeur voor een aandachtsgebied":** Je mag een voorkeur doorgeven. Dat is een advies. Het bestuur weegt het mee en beslist zelf.

**Uitleg onder het veld bedrag:** Vul zelf een bedrag in. We stellen geen bedrag voor.

**Kosten:** Een deel van ongeoormerkte giften kan nodig zijn voor de kosten van Naberschap, zoals de accountant en de administratie. Elk jaar maken we zichtbaar hoe die kosten zich verhouden tot wat er is besteed.

**Status:** Stichting Naberschap is in oprichting. De ANBI-status is nog niet toegekend.

## 9. Terminologie

- Gebruik **AlgemeenFonds** (één woord) zoals de Notitie AlgemeenFonds en de Stelselnotitie. Mathieu schrijft "Algemeen Fonds". Bevestig welke schrijfwijze het Lexicon voorschrijft en maak de site overal gelijk.
- Gever, inbrenger, gift (niet schenking, niet doneren, geen donateur), bestuur, aandachtsgebied, besteding of bestemming (niet Initiatief), Fonds op Naam. Nooit Geld Deler op deze site.

## 10. Controle voor oplevering

1. Staat er op elke giftpagina "Stichting Naberschap (in oprichting)" en nergens "ANBI" of "aftrekbaar"?
2. Is er geen bedrag voorgeselecteerd en geen urgentie?
3. Is het verschil met een Fonds op Naam zichtbaar, en staat "Begin je eigen Fonds op Naam" boven de giftknop op een voorbeeldpagina?
4. Staat er nergens dat de BV iets ontvangt of niets ontvangt? (Zeg: de gift gaat rechtstreeks naar Stichting Naberschap.)
5. Voldoet alles aan de WCAG: labels bij velden, knoppen van 44px, zichtbare focus, foutmeldingen in woorden?
6. Is de pagina nog op noindex?

## 11. Open punten (niet zelf invullen)

1. Belastingadviseur: is besteding van ongeoormerkte middelen "in het boekjaar na ontvangst" een passende invulling van "binnen redelijke termijn", en hoe verantwoord je de kosten uit het AlgemeenFonds in de jaarrekening? (Notitie AlgemeenFonds §8.)
2. Bestuur, na oprichting: beleid voor het aanvaarden van giften, inclusief giften van bedrijven die ook Sponsor zijn, en de werving van de startgift.
3. Betaalroute, betaalmethoden en de plaats van het betaalscherm (op naberschap.nl of via het platform). Het laatste botst nu met Stelselnotitie §7.
4. De lijst met aandachtsgebieden voor de keuzelijst (Kwalificatietabel v3).
5. Knoptekst: "Gift" in plaats van "Doneren" bevestigen.
6. Schrijfwijze AlgemeenFonds of Algemeen Fonds.
7. Mag een derde ooit bijdragen aan een bestaand Fonds op Naam? Zo ja, vastleggen in het Fondsreglement en toetsen bij de notaris. Tot dan niet aanbieden.
