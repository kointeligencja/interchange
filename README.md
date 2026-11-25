# INTERCHANGE — działająca implementacja v1.10

**Status: wersja do przeglądu zespołowego, nie zatwierdzona publikacja.**

36 tematów o transformacji AI, sześć linii, własna mapa SVG i spokojne strony do czytania. To rzeczywisty interfejs HTML/CSS/JavaScript z pełną treścią, a nie obraz makiety. Projekt realizuje kierunek „Everything is neutral except the network”.

## Zmiany v1.10 — wzbogacenie 6 stacji o badanie The Anthropic Institute (*Working with AI*)

Wydanie v1.10 dodaje rodzinę źródeł **S62** (Nathan Wilmers, Maxim Massenkoff i Peter McCrory, The Anthropic Institute — *Working with AI*, 23 listopada 2026, z bezpośrednim linkiem do oryginału na `anthropic.com/research/working-with-ai`) oraz 6 perspektyw dowodowych z dosłownymi cytatami sprawdzonymi ze stroną kanoniczną (66 wywiadów w 58 firmach w USA):
- **AI-01**: wartość biznesowa AI koreluje ze skalą zmiany organizacyjnej ($r = +0{,}39$ w ok. 300 wdrożeniach) i pochodzi głównie z ekspansji biznesu (55%), a nie redukcji etatów (2% zwolnień, 19% cięć kosztów, 19% brak wartości) (`anthropic-org-change-drives-value`).
- **AI-07**: oddolni użytkownicy nie mają mandatu do przebudowy procesów międzywydziałowych; firmy o najwyższej wartości łączą decyzje zarządcze z poszerzaniem ról do pełnej odpowiedzialności end-to-end (`anthropic-broadening-roles-and-authority`).
- **AI-10**: kwalifikacja trendu citizen-builderów z `S59` — aplikacje budowane przez osoby nietechniczne grzęzną na ostatniej mili (59 wzmianek o infrastrukturze, utrzymaniu i bezpieczeństwie) oraz w pułapce utrzymania zamienników taniego SaaS, dopóki IT nie zbuduje wspólnych, bezpiecznych szyn hostingowych i dostępu do danych (`anthropic-vibe-coded-last-mile-and-infra`).
- **AI-12**: kwalifikacja kontraktu adaptacyjnego z `S59` w zwykłych przedsiębiorstwach — opór pracowników (43 wzmianki) wynika z racjonalnych obaw przed utratą roli (2/3 firm ograniczyło rekrutację, 9 obcięło zewnętrznych/offshore kontraktorów), przerzucaniem trudniejszych wyjątków, ukrywaniem „secret sauce” i nadzorem typu panoptikon (`anthropic-resistance-surveillance-and-incentives`).
- **AI-35**: sztywne automatyzacje i chatboty starzeją się w „zombie apps” w ciągu ok. 3 miesięcy wraz z postępem modeli, podczas gdy trwałe systemy wymagają ciągłego utrzymania przez ekspertów domenowych po wdrożeniu (`anthropic-zombie-apps-and-moving-bottlenecks`).
- **AI-36**: te same narzędzia w tej samej branży (trzy średnie kancelarie prawne) dają skrajnie różne wyniki, a nierównomierne przyspieszenie rozbija sąsiednie zespoły i procedury SOP („Claude grenades”, 20 wzmianek o nienadążających zespołach) (`anthropic-uneven-velocity-and-local-context`).

Zastrzeżenie: jakościowa, niereprezentatywna próba 66 wywiadów w 58 firmach (klienci Anthropic w USA, większe firmy z nadreprezentacją software i finansów względem Census BTOS); oceny wartości, zmian organizacyjnych i wąskich gardeł pochodzą z deklaracji rozmówców zakodowanych automatycznie przez LLM.

Łącznie: 53 rodziny źródeł i 112 przypisanych perspektyw (89 pozycji w uniwersalnym indeksie semantycznym Jev).

## Zmiany v1.9 — wzbogacenie 5 stacji o esej DeepMind Institute (*The Economics of Intelligence*)

Wydanie v1.9 dodaje rodzinę źródeł **S61** (Alex Imas, Andrew Koh i Shane Legg, DeepMind Institute — *The Economics of Intelligence: How and when does AGI lead to economic transformation?*, 29 października 2026, z bezpośrednim linkiem do oryginału na `institute.deepmind.com`) oraz 5 perspektyw dowodowych z dosłownymi cytatami sprawdzonymi ze stroną kanoniczną:
- **AI-05**: płace i struktura ról zmieniają się przed widoczną restrukturyzacją firm i makrostatystykami zatrudnienia (`deepmind-wages-move-before-org-charts`).
- **AI-08**: koordynatorzy jako mnożniki „inteligencji mozaikowej” (+32% przewagi par komplementarnych nad losowymi w teście 100 osób i 6 domen) — ograniczanie tarcia na przekazaniach między specjalistami (`deepmind-coordinators-as-mosaic-multipliers`).
- **AI-13**: nawet przy AI przewyższającym każdego specjalistę z osobna (*Supercompetent AI*), przy ograniczonej koordynacji przewaga ludzi przesuwa się ku osądowi, wyznaczaniu kierunku, architekturze koordynacji i sektorowi relacyjnemu (`deepmind-supercompetent-human-advantage`).
- **AI-25**: skorelowane błędy kopii tego samego modelu i potrzeba ewaluacji „organizacji agentów” (podział pracy, czyste przekazanie kontekstu, wyłapywanie błędów zamiast ich kumulowania) (`deepmind-organization-level-benchmarks`).
- **AI-28**: rozdzielenie kompetencji od koordynacji w prawach skalowania organizacyjnego — poniżej progu *supercooperative* dodawanie kolejnych agentów szybko wpada w malejące przychody (`deepmind-coordination-vs-competence-scaling`).

Zastrzeżenie: esej teorii równowagi (oparty na pracy *Organizing Intelligence*, `arXiv:2611.05417`) z jednym stylizowanym badaniem quizowym (N=100) oraz zastrzeżeniem DMI, że nie jest to oficjalne stanowisko Google.

Łącznie: 52 rodziny źródeł i 106 przypisanych perspektyw (88 pozycji w uniwersalnym indeksie semantycznym Jev).

## Zmiany v1.8 — wzbogacenie 5 stacji o esej a16z (*Databricks & the Future of the Firm*)

Wydanie v1.8 dodaje rodzinę źródeł **S60** (Ben Horowitz i Michael McGuiness, Andreessen Horowitz — *Databricks & the Future of the Firm*, 27 października 2026, z bezpośrednim linkiem do oryginału na a16z.com) oraz 5 perspektyw dowodowych z dosłownymi cytatami sprawdzonymi z kanoniczną stroną:
- **AI-08**: zasada Herberta Simona — scentralizowany stan i zabezpieczenia umożliwiają zdecentralizowane działanie; ludzie koordynują się z rejestrem, a nie przez centralny zespół (`horowitz-centralized-state-decentralized-action`).
- **AI-13**: „druga rewolucja menedżerska” (odwrócenie tezy Burnhama) — egzekucja i osąd są komplementarne; zarządzanie traci monopol, nie cel; zastrzeżenie Alego Ghodsiego wobec modelu Block (`horowitz-everyone-a-manager`).
- **AI-14**: wspólny magazyn danych operacyjnych i analitycznych oraz izolowane, jednorazowe gałęzie baz danych do eksperymentów agentów (`horowitz-shared-storage-branching`).
- **AI-15**: utrzymywana ontologia z rankingiem autorytetu definicji (autor, zasięg użycia, aktualność) zamiast wyszukiwania po wszystkich danych (`horowitz-ontology-authority`).
- **AI-32**: „suwerenna firma” — przenośność tego, czego firma się nauczyła (definicje, uprawnienia, ocenione przypadki, korekty ludzi), a nie tylko interfejsu modelu (`horowitz-sovereign-firm`).

Zastrzeżenie: autorzy są inwestorami Databricks (a16z prowadził rundy A i C). Metryki firmy i wynik OntoRank (ok. 50% → 84,5%) są deklaracjami własnymi; perspektywy opisują mechanizmy, nie rekomendację dostawcy.

Łącznie: 51 rodzin źródeł i 101 przypisanych perspektyw (87 pozycji w uniwersalnym indeksie semantycznym Jev).

## Zmiany v1.7 — wzbogacenie 6 stacji o badanie The Anthropic Institute (*How Employment is Changing at Anthropic*)

Wydanie v1.7 dodaje rodzinę źródeł **S59** (Nathan Wilmers, Regina Catipon, Maxim Massenkoff, Peter McCrory — *How Employment is Changing at Anthropic*, z bezpośrednim linkiem do raportu PDF) oraz 6 perspektyw dowodowych:
- **AI-05**: weryfikacja produktywności metodą staggered adoption (192 adoptujących vs 74 nieadoptujących z efektami stałymi osoby i miesiąca) oraz 6 wskaźników jakości kodu (brak wzrostu rewertów i usunięć kodu w ciągu 90 dni), przy jednoczesnym wzroście czasu spędzanego na spotkaniach o 20% (+16% dla inżynierów IC) wskutek ujawniania problemów systemowych i zarządczych (`anthropic-within-person-quality-audit`).
- **AI-10**: 45-krotny wzrost sesji kodowania agentowego wśród pracowników nietechnicznych (z 2 do 90 miesięcznie w sprzedaży, finansach, dziale prawnym i rekrutacji) budujących własne dashboardy i integracje MCP (`anthropic-nontechnical-builders`).
- **AI-12**: kontrakt adaptacyjny w organizacji AI-native — łączenie partycypacji kapitałowej z wewnętrznym systemem wczesnego ostrzegania (early warning system) oraz priorytetem wewnętrznej realokacji pracowników (+50% r/r mobilności międzywydziałowej) zamiast płytkiej automatyzacji kosztowej (`anthropic-redeployment-bargain`).
- **AI-13**: spadek udziału juniorów w nowych rekrutacjach technicznych z 27% do 9% (oraz w zatrudnieniu technicznym z 21% do 14%) przy przesunięciu kart oceny kandydatów z wąskiej egzekucji domenowej na autonomię i osąd (`anthropic-junior-squeeze-and-judgement`).
- **AI-17**: wymóg obserwowalności ludzkich decyzji — prywatne ustalenia poza logami pozbawiają agentów kontekstu, a nieaktualna dokumentacja powoduje błędne kierowanie zadań (wzrost liczby plików ze stałymi instrukcjami dla agentów do 8500+) (`anthropic-context-observability`).
- **AI-28**: ludzka uwaga jako główne wąskie gardło przy relacji godzin pracy agentów do ludzi 6:1 — agenci spędzają ok. 80% czasu sesji interaktywnych bezczynnie czekając na człowieka, przeczytanie wygenerowanego tekstu wymagałoby ponad połowy tygodnia pracy, a udział „meta-pracy” (budowa monitorów, specyfikacji i pętli nadzoru) wzrósł z 10% do 22% sesji (`anthropic-attention-bottleneck`).

Łącznie: 50 rodzin źródeł i 96 przypisanych perspektyw (86 pozycji w uniwersalnym indeksie semantycznym Jev).

## Zmiany v1.6 — semantyczny silnik wyszukiwania Jev (TypeSafe)

Wydanie v1.6 zastępuje dawne wyszukiwanie leksykalne semantycznym rankingiem **Jev** od TypeSafe AI (według wzorca z projektu `read.atharvashah.com` Atharvy Shaha):
- **Jeden uniwersalny ranking:** wyszukiwanie analizuje kontekstowe znaczenie zapytania i szereguje jednocześnie całą bazę **36 stacji** oraz **40 źródeł** (76 pozycji).
- **Procent dopasowania (% match):** każda znaleziona stacja i źródło wyświetla typowane prawdopodobieństwo (`0–100% match`) wraz z graficznym wskaźnikiem siły korelacji.
- **Filtrowanie zakładek:** szybkie przełączanie widoku między wszystkimi pozycjami (`All`), samymi problemami (`Stations`) a autorami/literaturą (`Sources`).
- **Endpoint serverless (`api/search.js`):** obsługa zapytań z modelu Jev z wbudowanym deterministycznym fallbackiem zapewniającym ciągłość działania.

## Zmiany v1.5 — operacyjne wzbogacenie 6 stacji (Emergence Capital / Julien Bek / Konstantine Buhler)

Wydanie v1.5 dodaje 3 rodziny źródeł (**S47**, **S48**, **S49**) oraz 7 perspektyw dowodowych:
- **AI-01**: budżety narzędzi vs pracy ($500 mld SaaS vs $10 bln usług); copilot sprzedaje narzędzie, autopilot sprzedaje gotową pracę (**S47** / Julien Bek).
- **AI-05**: metryka HURT (Human Unit Review Time) mierząca czas ludzkiej rewizji na jednostkę deliverable'a jako twardy wskaźnik dojrzałości autonomii (**S48** / Emergence Capital).
- **AI-06**: pułapka Mirage PMF przy niesubsydiowanym ludzkim nadzorze i kosztach inferencji (uczciwy COGS a marże 30–50%) (**S48**) oraz paradoks Jevonsa w myśleniu maszynowym — spadek kosztu kognicji indukuje eksponencjalny popyt na analizę (**S49** / Konstantine Buhler).
- **AI-09**: paired engineering — inżynierowie oprogramowania bezpośrednio obok ekspertów domenowych w pętli dostarczania, zamieniający wyjątki w kod i ewaluacje (**S48** / Emergence Capital).
- **AI-13**: utowarowienie surowej inteligencji modeli (drafting, synteza) przy trwałej wartości osądu operacyjnego, kontekstu decyzyjnego i odpowiedzialności powierniczej (**S47** / Julien Bek).
- **AI-29**: autorskie platformy delivery rozbijają liniową zależność zatrudnienia i przychodów, dążąc do marż 70–80% (**S48** / Emergence Capital).

Łącznie: 40 rodzin źródeł i 81 przypisanych perspektyw.

## Zmiany v1.4 — operacyjne wzbogacenie 4 stacji (Bartek Pucek / Thinking Companies)

Wydanie v1.4 dodaje rodzinę źródeł **S46** (Bartek Pucek — *Thinking Companies*) oraz 4 perspektywy dowodowe:
- **AI-02**: iluzja lokalnego copilota i wzmacnianie sprzeczności między silosami (sprzedaż deklarująca terminy, których zakupy nie mogą spełnić).
- **AI-07**: rozpakowanie wiązki stanowiskowej (*job bundle*) a granica odpowiedzialności i uprawnień (*fiduciary anchor* / Bérenger Teboul-Danguin: klient kupuje kogoś, kto odpowiada za wynik).
- **AI-28**: filtr marnotrawstwa przy tanim myśleniu maszynowym (tani koszt kognitywny ułatwia produkcję niepotrzebnych analiz; kryterium: czy wysiłek zmienia decyzję lub wynik).
- **AI-31**: przejście od sprzedaży narzędzi do pracujących procesów (Julien Bek) oraz compounding delivery i utrwalanie metod operacyjnych po wdrożeniu (Emergence Capital).

Łącznie: 37 rodzin źródeł i 74 przypisane perspektywy.

## Zmiany v1.3 — operacyjne wzbogacenie 9 stacji (Ismail / Ju / Sehgal)

Wydanie v1.3 jest bezpośrednią realizacją zasady żywego przewodnika (*living guide, not a finished checklist*): 36 stacji stanowi stabilną strukturę problemów, a nowe materiały pogłębiają je przez dodanie pożytecznego nowego lensu, kwalifikacji, wyzwania, kontrargumentu lub praktycznej alternatywy — z celem głębszego zrozumienia, a nie dłuższego spisu literatury.

Dodano 5 nowych rodzin źródeł (S41–S45) oraz 10 przypisanych perspektyw dowodowych do 9 stacji, wzbogacając diagnozy i pytania o warunki kontekstowe (AI-04), kulturę metryk wejściowych i rolę kontr-przypadku (AI-05), utratę ścieżki terminowania (AI-13), inwersję warstwy danych (AI-14), rejestrację śladów decyzyjnych oraz kontrargument Alloy Partners dot. delayeringu (AI-17), stopniowaną autoryzację i klin powierniczy (AI-24), wąskie gardła w kolejkach zatwierdzeń, niezmieniony cycle time oraz analizę monotoniczności zadań Haranga Ju (AI-28), instytucjonalną ochronę kontr-tezy w pilotach (AI-30) oraz koszty migracji i własność dziennika zdarzeń Ishaana Sehgala / Omnara (AI-32). Łącznie: 36 rodzin źródeł i 70 przypisanych perspektyw.

[Zasady aktualizowania i atrybucji](docs/ORIGINS-AND-UPDATES.md) · [Tekst About](ABOUT.md) · [Changelog](docs/CHANGELOG.md)

## Otwórz od razu

Otwórz **`INTERCHANGE.html`** w przeglądarce. To jeden samodzielny plik zawierający wszystkie strony, style, wyszukiwanie i nawigację. Nie wymaga instalacji ani uruchamiania serwera. Do otwierania oryginalnych źródeł potrzebny jest internet.

Podgląd załącznika w komunikatorze może nie wykonywać JavaScript. W takim przypadku zapisz plik na komputerze i otwórz go w zwykłej przeglądarce. Zakładki są lokalne; przy zablokowanej pamięci przeglądarki interfejs informuje o ograniczeniu.

## Uruchom projekt lokalnie

Wymagany Node.js **22.12 lub nowszy**. Domyślna ścieżka nie wymaga `npm install`:

```sh
cd interchange-app
npm run dev
```

Otwórz `http://localhost:4173/`. Polecenie buduje stronę, uruchamia serwer i obserwuje zmiany w `src/` oraz `content/`. Po przebudowaniu odśwież przeglądarkę; nie ma automatycznego HMR.

Aby tylko obsłużyć już zbudowane pliki:

```sh
npm start
```

Aby odtworzyć `dist/` i samodzielny plik HTML:

```sh
npm run build
```

## Co działa

- Sześć ciągłych tras SVG i wszystkie 36 stacji; podgląd po najechaniu/fokusie, wybór linii, przejście do artykułu.
- 36 pełnych dokumentów: diagnoza, pytania, perspektywy źródłowe, możliwe działania, ograniczenia, przykłady hipotetyczne i powiązane tematy.
- Pełny indeks, wyszukiwanie lokalne i semantyczne (Jev), katalog oryginalnych źródeł, trzy ścieżki czytania i dziesięć proponowanych powiązań.
- Mobilna lista stacji na pionowej linii, obsługa klawiatury, ograniczonego ruchu oraz użyteczny indeks bez JavaScript.
- Zapisywanie tematów w tej przeglądarce, kopiowanie linku i szablonu roboczego; bez kont i analityki.
- Budowanie statycznych stron, walidacja danych, testy, kontrola linków wewnętrznych, obsługa subścieżki i blokada niezatwierdzonej publikacji.

Wersja zawiera **64 strony**, **52 rodziny źródłowe z dostarczonymi publicznymi URL** i **106 przypisanych perspektyw** (88 obiektów w indeksie semantycznym Jev). Te liczby nie oznaczają niezależnej weryfikacji źródeł. Treść i interfejs pozostają po angielsku, zgodnie z materiałem wejściowym. Instrukcja dla zespołu jest po polsku.

## Architektura — ważne rozróżnienie

**Uruchomiona i przetestowana ścieżka:** statyczny kompilator Node, HTML, autorski SVG, CSS oraz JavaScript sprawdzany przez TypeScript. Wyszukiwanie jest lokalne i deterministyczne.

**Opcjonalny adapter:** w `astro/` jest integracja z Astro, wykorzystująca te same szablony i dane. Nie została skompilowana w tym środowisku, ponieważ instalacja pakietów npm była niedostępna. Pagefind nie jest aktywnym silnikiem tej wersji. Nie przedstawiamy adaptera jako przetestowanego wdrożenia Astro.

Pełne wyjaśnienie i ścieżka migracji: [IMPLEMENTATION](docs/IMPLEMENTATION.md).

## Orientacja w repozytorium

| Ścieżka | Znaczenie |
|---|---|
| `INTERCHANGE.html` | Samodzielna, klikalna wersja do przeglądu |
| `dist/` | Gotowe strony i zasoby do serwowania HTTP |
| `content/about.json` | Edytowalne pochodzenie projektu i zasady aktualizowania |
| `content/stations/` | 36 oddzielnych rekordów tematów |
| `content/evidence/` | Przypisane perspektywy i ich ograniczenia |
| `content/sources/` | Tytuły, autorzy, URL i status kontroli źródeł |
| `src/data/map-layout.json` | Współrzędne tras, stacji i etykiet |
| `src/data/transfers.json` | Osobne relacje redakcyjne |
| `src/render.mjs` | Komponenty i szablony renderowane do HTML |
| `src/scripts/` | Interakcje przeglądarkowe i router wersji jednoplikowej |
| `src/styles/style.css` | Tokeny, layout, responsywność i stany interakcji |
| `scripts/` | Build, serwer, walidacja i kontrola linków |
| `tests/`, `reports/` | Testy i wyniki faktycznych uruchomień |
| `screenshots/` | Zrzuty działającej implementacji, nie generowane makiety |

## Przed publikacją

Ta wersja nie została umieszczona pod publicznym adresem. Wszystkie tematy są nadal robocze. Polecenie `npm run build:public` **celowo kończy się błędem**, dopóki treść, źródła i odpowiednie fragmenty nie przejdą wymaganych kontroli. Nie usuwaj blokady tylko po to, aby build przeszedł.

`noindex` nie zabezpiecza dostępu. Zespołowy preview umieszczaj za kontrolą dostępu hostingu. Nigdy nie publikuj całego repozytorium jako katalogu strony; serwuj tylko `dist/`.

## Dokumenty dla zespołu

[Implementacja i zgodność z PRD](docs/IMPLEMENTATION.md) · [Edycja treści](docs/CONTENT-EDITING.md) · [Wdrożenie](docs/DEPLOYMENT.md) · [Raport testów](docs/TEST-REPORT.md) · [Zmiany](docs/CHANGELOG.md)


## Najlepszy sposób udostępniania

Do przeglądu: GitHub + chroniony Vercel Preview. Do szybkiego jednorazowego share: upload zawartości `dist/` do Vercel Drop. Po zatwierdzeniu: własna domena i automatyczny deployment z `main`. Szczegóły: [DEPLOYMENT](docs/DEPLOYMENT.md).
