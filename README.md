# GeoSamm 2.1

**Geograafiliste koordinaatide õpiassistent ja õpetaja õpianalüütika**

See on brauseris töötav õppeprototüüp. Õpilane saab harjutada geograafiliste koordinaatide lugemist ning antud koordinaatide järgi kaardilt õige punkti leidmist. Õpetaja näidisvaates saab uurida sooritusi, võimalikke veakohti, abistamise kasutamist ja klassi mustreid.

## Käivitamine

Ava fail `index.html` veebibrauseris. Paigaldamine ja API-võti ei ole vajalikud.

## GitHubi üleslaadimine

1. Loo GitHubis uus hoidla (repository), näiteks `geosamm`.
2. Paki ZIP-fail lahti.
3. Ava hoidlas **Add file → Upload files** ja laadi üles ZIP-ist saadud failid (`index.html`, `README.md`, `.nojekyll`) **otse hoidla juurkausta**. Ära laadi üles ZIP-faili ennast ega lisa failidele täiendavat alamkausta.
4. Kinnita failide lisamine (**Commit changes**).

## Avaldamine GitHub Pagesis

1. Ava GitHubi hoidlas **Settings → Pages**.
2. Jaotises **Build and deployment** vali **Deploy from a branch**.
3. Vali haru **main** ja kaust **/(root)** ning salvesta (**Save**).
4. GitHub kuvab seejärel avaliku veebiaadressi; tavaliselt on see kujul `https://KASUTAJANIMI.github.io/geosamm/`.

GitHubi kasutajaliidese nimed võivad ajas muutuda. Tavapärase GitHub Pagesi avaldamise korral on veebileht avalikult ligipääsetav.

## Prototüübi piirangud

- Tegemist on reeglipõhise prototüübiga, mitte generatiivse AI-vestlusassistendiga.
- Katseandmeid hoitakse kasutaja brauseris, eri arvutite vahel neid ei sünkroniseerita.
- Õpetaja vaates on olemas väljamõeldud näidisandmed; neid ei tohi esitada tegelike õpilastulemustena.
- Väärarusaamade hinnangud on esialgsed hüpoteesid, mitte kinnitatud diagnoosid.
- **Ära sisesta päris õpilaste nimesid ega tundlikke isikuandmeid.** Koolis kasutamiseks tuleb eraldi kavandada autentimine, turvaline andmetöötlus ja andmekaitse.

## Failid

- `index.html` — kogu rakendus ühes HTML-failis (sh stiilid ja JavaScript).
- `README.md` — projekti kirjeldus ja avaldamisjuhend.
- `.nojekyll` — võimaldab GitHub Pagesil faile otse staatilise veebina serveerida.
