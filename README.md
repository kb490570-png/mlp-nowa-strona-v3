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
