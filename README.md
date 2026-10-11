# MLP – projekt poglądowy v3 „Ewolucja obecnej strony” (11.10.2026)

Statyczny projekt poglądowy nowej strony głównej mlp.opole.pl: ta sama identyfikacja (logo, czerwień #d65050, granat/grafit, Raleway + Source Sans, zdjęcia z biblioteki mediów, kolejność sekcji), w wykonaniu premium. `noindex, nofollow`, etykieta „Projekt poglądowy”, formularz nieaktywny.

## Analiza obecnej strony (11.10.2026, publiczny GET)
- Szablon Sydney (WordPress), nagłówek przezroczysty na sliderze: logo MLP, menu wielkimi literami (START, KURSY I KOREPETYCJE, TŁUMACZENIA, PRACA, O FIRMIE, KONTAKT, BLOG, flagi EN/DE).
- Slider pełnoekranowy, 3 zdjęcia: budka telefoniczna + Big Ben („ZNAJDŹ CZAS NA JĘZYK”), dziewczyna przed Big Benem („KURSY I KOREPETYCJE”), pióro i dokument („TŁUMACZENIA”); czerwony przycisk „ZOBACZ WIĘCEJ”.
- Kolory: czerwony akcent #d65050 (przyciski, podkreślenia nagłówków, pas social, pas 3 CTA), tekst granatowy #233452, ciemne sekcje #2b2b2b (atuty, stopka), tła białe/#f9f9f9; kafle atutów w kolorach niebieski/zielony/błękit/czerwony z ikonami Font Awesome.
- Fonty: Raleway (nagłówki, często wersaliki) + Source Sans Pro (tekst).
- Kolejność sekcji: slider → H1 + tekst o szkole + zdjęcie budynku → widżet Google „DOSKONAŁA, 92 opinie” → „Nasza oferta” (4 karty ze zdjęciami: kursy, korepetycje, tłumaczenia, egzaminy) → „Atuty” (ciemne tło, kafle) → opinie kursantów (slider) → pas social → bloki tekstu SEO ze zdjęciami flag → czerwony pas „Poznaj nas / Współpracuj z nami / Zadaj pytanie” → Aktualności (Orły Kształcenia, Parlament Europejski, Matura 2022) → Blog (karuzela) → stopka (adres, partnerzy/odznaka Orły, formularz, lista „Tłumacz przysięgły …”).
- Odczucie: wiarygodna, bogata w treść, ale datowana – drobna typografia, wąskie marginesy, kolorowe kafle bez spójności, dużo tekstu SEO, baner cookies zasłania pierwszy ekran.

## Co zachowano / co poprawiono – patrz raport końcowy.

## Zdjęcia (wszystkie z biblioteki mediów mlp.opole.pl, kopia wp-content/uploads z 10.10.2026)
profesjonalna-szkola-jezykowa.jpg, kursy-korepetycje.jpg, tlumaczenia.jpg (slider), mainpage-kursy2.jpg, mainpage-korepetycje.jpg, mainpage-tlumaczenia-1.jpg, mainpage-kursy.jpg (oferta), szkola-jezykow-obcych-opole-metropolitan-language-professionals.jpg (budynek), sala1_panorama4_2.jpg (sala – do potwierdzenia), parlament-europejski.jpg, matura-jezyk-obcy.jpg, KSZTAŁCENIA-LOGO-2019, 2024-tlumaczenia200.png (Orły Tłumaczeń 2024), odznaka Oferteo 2023, Karta Opolska Rodzina, logo MLP (kolor i białe litery). Brak zdjęć stockowych spoza strony MLP.

## Treści
Teksty skrócone/zredagowane z obecnej strony (home, /o-firmie/, /tlumaczenia/, kursy). Fakty: 92 opinie „Doskonała”, PE od X 2017 (niemiecki, hiszpański), Orły Kształcenia 2019, Orły Tłumaczeń 2024 (odznaka na stronie), Oferteo 2023, 93% średnia zdawalność matury (aktualność „Matura 2022”), 500+ uczestników EFS 2010–2015, lista klientów z /o-firmie/. Opinie Google cytowane dosłownie (Agata Nowocień – fragment). Opinie kursantów – dosłownie z sekcji „Opinie klientów” obecnej strony.
Do uzupełnienia: godziny otwarcia.

## Fonty
Raleway (variable, wght 300–800) i Source Sans 3 (variable, 400–700), SIL OFL, self-hosted, subset Latin + polskie znaki.

## Technika
HTML/CSS + ~1.5 KB JS (nagłówek przy przewijaniu, scroll-reveal, liczniki, crossfade slidera; pierwszy slajd statyczny i preloadowany, kolejne doładowywane 2,5 s po `load`; prefers-reduced-motion wyłącza animacje).
shots/ – v3 desktop 1440×900 i mobile 390×844 @2x (first_screen + full_page). current/ – zrzuty obecnej strony. compare/ – porównanie przed/po.

## Rewizja r2 (11.10.2026) – większa różnorodność zdjęć (uwaga Artura: „Lepiej tylko większa różnorodność zdjęć”)
Poprzednia wersja zachowana lokalnie jako mockup-v3-r1. Układ i styl bez zmian; dodano zdjęcia.
Zasady: najpierw biblioteka mediów MLP (przejrzane wszystkie ~165 zdjęć z wp-content/uploads w kopii z 10.10.2026), potem darmowe zdjęcia Unsplash/Pexels (licencje pozwalają na użytek komercyjny, bez obowiązku atrybucji – atrybucja poniżej).
Zdjęcia stockowe (także licencjonowane przez MLP zdjęcia Fotolia z ich biblioteki) NIE są podpisywane jako kursanci/kadra MLP – mają dopisek „fot. ilustracyjne”/„zdjęcie ilustracyjne” w alt. Wspólna lekka korekta kolorów (saturacja −8%, kontrast +4%, delikatne ocieplenie) dla spójności.
W stopce: „zdjęcia ilustracyjne: Unsplash/Pexels”.

| Plik (assets/) | Miejsce | Źródło |
|---|---|---|
| s1-*, s1m-* | hero slajd 1 „Kursy” | MLP: profesjonalna-szkola-jezykowa.jpg (obecny slider) |
| h2-*, h2m-* | hero slajd 2 „Dzieci” | Pexels 5428152, Tima Miroshnichenko – https://www.pexels.com/photo/5428152/ |
| h3-*, h3m-* | hero slajd 3 „Firmy” | MLP: Fotolia_105493358 (biblioteka mediów, Fotolia) |
| h4-*, h4m-* | hero slajd 4 „Języki” (Paryż, Sekwana) | Unsplash IlHhcdWWzwg, Lukas Konvica – https://unsplash.com/photos/IlHhcdWWzwg |
| h5-*, h5m-* | hero slajd 5 „Tłumaczenia” | MLP: tlumaczenia.jpg (obecny slider) |
| of-kursy-590 | karta Kursy językowe | MLP: mainpage-kursy2.jpg |
| of2-korep-590 | karta Korepetycje | MLP: Fotolia_123490641 |
| of2-tlum-590 | karta Tłumaczenia | MLP: Fotolia_92433221 |
| of2-egz-590 | karta Egzaminy | MLP: school.jpg |
| au-dzieci-* | kafel „Angielski dla dzieci” | Pexels 8613091, Yan Krukau – https://www.pexels.com/photo/8613091/ |
| au-dorosli-* | kafel „Angielski dla dorosłych” | Pexels 5756752, RDNE Stock project – https://www.pexels.com/photo/5756752/ |
| au-firmy-* | kafel „Szkolenia językowe dla firm” | MLP: Fotolia_116840464 |
| lg-en-480 | karta English (autobus londyński) | MLP: bus-84711.jpg |
| lg-de-480 | karta Deutsch (Brama Brandenburska) | Unsplash IK6V4vmRYIg, Shalev Cohen – https://unsplash.com/photos/IK6V4vmRYIg |
| lg-es-480 | karta Español (Sagrada Família) | Unsplash bNW-YvtON_Q, Ahmed Salem – https://unsplash.com/photos/bNW-YvtON_Q |
| lg-fr-480 | karta Français (wieża Eiffla) | Unsplash Zve-pSbRKbs, Fabio Fistarol – https://unsplash.com/photos/Zve-pSbRKbs |
| lg-it-480 | karta Italiano (Koloseum) | Unsplash YF0-bW3Qpds, Marco Grosso – https://unsplash.com/photos/YF0-bW3Qpds |
| lg-pl-480 | karta Polski (wieża ratusza w Opolu) | Pexels 35539566, MrGajowy3 Teodor – https://www.pexels.com/photo/35539566/ |
| at-grupa-760 | sekcja Atuty | MLP: Fotolia_139455449 |
| ga-kids-900 | galeria – Angielski dla dzieci i młodzieży | Pexels 29242202, This And No Internet 25 – https://www.pexels.com/photo/29242202/ |
| ga-konkurs-600 | galeria – Konkurs Wymowy Angielskiej 2017 (prawdziwe wydarzenie; MLP ufundowało nagrody – wg wpisu w Aktualnościach) | MLP: maleDSC_0690.jpg |
| ga-adults-600 | galeria – Konwersacje dla dorosłych | Pexels 5905527, Katerina Holmes – https://www.pexels.com/photo/5905527/ |
| ga-biz-600 | galeria – Szkolenia dla firm | Unsplash -Lzdk59aldE, Vitaly Gariev – https://unsplash.com/photos/-Lzdk59aldE |
| ga-bcn-600 | galeria – Hiszpański (Barcelona) | Unsplash u5DXeHhcQUc, Salma Abdelnaby – https://unsplash.com/photos/u5DXeHhcQUc |
| tl-doc-760 | sekcja Tłumaczenia | MLP: Fotolia_78148463 |
| news-pe2-600 | Aktualności – Parlament Europejski | MLP: 23721890_…_n.jpg |

Wydajność: WebP w rozmiarach responsywnych, lazy-load poniżej pierwszego ekranu, slajd 1 statyczny + preload; slajdy 2–5 dociągane pojedynczo (kolejny dopiero przed pokazaniem).
Pełna lista pobranych kandydatów: mockup-v3src/stock/sources.tsv; skrypt: mockup-v3src/mkimg_r2.py.
