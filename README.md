# naberschap-site

Website van Stichting Naberschap (in oprichting). Concept 0.3, niet vastgesteld door een bestuur.

- Statische site: `index.html` (alle pagina's in één bestand, hash-navigatie). Geen build, geen externe trackers.
- Alleen externe verbinding: Google Fonts (Poppins). Overweeg later zelf hosten.
- Staat op noindex (`robots.txt` en `X-Robots-Tag` in `vercel.json`) tot het bestuur de teksten heeft vastgesteld.
- Eigen GitHub-repository, eigen Vercel-project en eigen domein (naberschap.nl). Niets gedeeld met de LustrumMoment- of Mondéall-site.

## Live zetten
1. Maak op GitHub een lege, private repository `naberschap-site`.
2. `git remote add origin <url>` en `git push -u origin main`.
3. Importeer de repository in Vercel (Framework Preset: Other, geen build command, output directory leeg).
4. Koppel naberschap.nl pas als het bestuur de teksten heeft vastgesteld en noindex bewust wordt weggehaald.

## Bronnen
`archief-concepten/` bevat het voorstel, de huisstijl en de projectinstructie waarop deze versie rust.
