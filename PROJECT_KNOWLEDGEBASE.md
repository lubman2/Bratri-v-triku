# AI Knowledgebase: Bratři v triku

## Co je to za projekt

Statická prezentační webová stránka založená na jedné dlouhé rešerši o studiu Bratři v triku. Cíl je převést odborný podklad do přehledné, rychle čitelné a veřejně publikovatelné formy.

## Primární zdroj pravdy

- `Bratri_v_triku_research.md`

## Hlavní obsahové teze

- Studio vzniklo `29. 5. 1945`.
- Rané období je úzce spojené s `Jiřím Trnkou`.
- Veřejně doložené profily studia je potřeba chápat minimálně ve dvou etapách: `1945–1991` a `1991–2011`.
- Důležité milníky jsou Trnkův odchod v roce `1946`, film `Stvoření světa` (`1957`) jako první český dlouhý kreslený film a porevoluční transformace značky.
- Významná díla pro veřejnou prezentaci: `Pérák a SS`, `Zvířátka a petrovští`, `Stvoření světa`, `Jak krtek ke kalhotkám přišel`, `O místo na slunci...`, `Ať žije myš`, `Kavárna`, `Pygmalion`.
- U novějších popularizačních textů je potřeba opatrnost u širších atribucí; pro přesnost se má vycházet hlavně z Filmového přehledu / NFA.

## UX a obsahová rozhodnutí pro web

- Web zůstává čistě statický: `index.html` + `styles.css`.
- Informační architektura je rozdělena na historii, milníky, etapy, osobnosti, výrobu, vybraná díla, ocenění, kompletní filmografii a zdroje.
- Stránka má lehčí a kompaktnější vizuální směr než první verze: světlejší plocha, menší bloky, méně dekorativní hutnost.
- Klíčové osobnosti mají být uváděny s profesí a konkrétním přínosem pro studio.
- Kompletní veřejně doložená filmografie je vypsaná přímo na stránce po letech.

## Deployment rozhodnutí

- Cílová platforma: `Vercel`
- Projekt nevyžaduje build krok.
- Repo má být publikováno pod GitHub účtem `lubman2`, jakmile bude platná autentizace.
