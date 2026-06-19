# Czarna Palarnia — strona-wizytówka

Portfolio: rzemieślnicza palarnia kawy speciality z Poznania.

## Styl
**Craft Editorial / Ziarnisty** — ciepła redakcyjna estetyka inspirowana kartami degustacyjnymi i etykietami kaw speciality. Asymetryczny układ, duży serif display (Newsreader), numeracja sekcji, skala palenia jako animowany wskaźnik, etykiety w stylu opakowań kawy.

Paleta: krem #efe6d8 · espresso #2a1d16 · terakota #c2502a · oliwka #7e7a4e · ink #241a13

Fonty: Newsreader (display) · Hanken Grotesk (body) · Space Mono (etykiety/mono)

## Sekcje
1. Nav (fixed, scrolled state)
2. Hero — asymetryczny, 12-kolumnowy, duże hasło, CTA
3. O palarni — rzemiosło, Probat P12, fakty
4. Nasze kawy — 4 single origin z kartami degustacyjnymi i skalą palenia
5. Subskrypcja — 3 plany (Odkrywca / Koneser / Kolekcjoner)
6. B2B / Dla kawiarni — oferta hurtowa
7. Gdzie pić i kupić — godziny + mapa OSM
8. Opinie
9. Formularz zamówienia
10. Footer z creditem

## Stack
- Astro 5
- Tailwind CSS 4 (przez @tailwindcss/vite)

## Komendy
```bash
npm install
npm run dev      # serwer dev http://localhost:4321
npm run build    # build produkcyjny → dist/
npm run preview  # podgląd builda
```

## Hosting
Hostowane na Vercel (wykrywa Astro automatycznie, build: `astro build`, output: `dist`).
