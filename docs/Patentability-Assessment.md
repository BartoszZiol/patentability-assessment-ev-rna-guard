# EV-RNA Guard: wstępne badanie patentowalności

> **Przykładowa koncepcja techniczna.** Projekt ma charakter edukacyjny. Nie przedstawia gotowego wynalazku, urządzenia ani wyników badań. Nie stanowi profesjonalnej opinii prawnej ani pełnego badania zdolności patentowej.

## 1. Przedmiot analizy

EV-RNA Guard to hipotetyczny system do analizy mikroRNA (miRNA) w pęcherzykach pozakomórkowych (EV) z osocza. Koncepcja zakłada mikroprzepływowy wychwyt pęcherzyków, oznaczenie miR-21 i miR-155, zastosowanie materiałów kontrolnych na różnych etapach procesu oraz ocenę hemolizy. W przypadku niespełnienia kryteriów jakości system nie powinien wydawać wyniku.

**Założona sekwencja procesu:**

1. Dodanie do próbki referencyjnych cząstek R-EV zawierających znane RNA.
2. Wychwyt EV na chipie mikroprzepływowym.
3. Uwolnienie i oczyszczenie RNA.
4. Dodanie odrębnego RNA kontrolnego R-POST po ekstrakcji.
5. Oznaczanie miRNA i wskaźnika hemolizy.
6. Przypisanie wyniku statusu ważny, nieważny lub do powtórzenia.

**Cechy F1–F8:** F1 osocze badane in vitro; F2 wychwyt EV na chipie; F3 oznaczanie miR-21 i miR-155; F4 kontrolne R-EV dodawane przed izolacją; F5 RNA R-POST dodawany po ekstrakcji; F6 kontrola hemolizy; F7 wspólna ocena kontroli; F8 wstrzymanie wyniku w razie błędu kontroli.

## 2. Zakres przeglądu

Analizę ograniczono do sześciu publikacji patentowych i jednej publikacji naukowej. Wykorzystano wybrane zastrzeżenia, opisy i przykłady, a kryteria oceny odniesiono do EPC. Nie przeprowadzono pełnego badania stanu techniki, rodzin patentowych, aktualnych statusów prawnych ani analizy FTO.

## 3. Wybrane dokumenty stanu techniki

| Dokument | Ujawnienie istotne dla koncepcji |
| --- | --- |
| [D1: US20150094357A1](https://patents.google.com/patent/US20150094357A1/en) | miR-21 i miR-155 w analizie schorzeń trzustki (zastrz. 1 i 12); nie dotyczy identycznego układu EV z osocza |
| [D2: CN114106978A](https://patents.google.com/patent/CN114106978A/en) | Mikroprzepływowy układ wychwytu egzosomów, w tym z użyciem aptamerów wiążących CD63 (zastrz. 1, przykłady 1 i 3) |
| [D3: EP3090059B1](https://patents.google.com/patent/EP3090059B1/en) | Kontrola hemolizy na podstawie miRNA i możliwość wyłączenia próbki (zastrz. 13–16 wersji B1) |
| [D4: WO2014036391A1](https://patents.google.com/patent/WO2014036391A1/en) | Cząstki kontrolne dodawane do próbki, współizolacja i ocena odzysku (zastrz. 1 i 5) |
| [D5: WO2020106853A1](https://patents.google.com/patent/WO2020106853A1/en) | Kontrole izolacji mikrocząstek oraz wzorzec RNA na etapie RT (zastrz. 1, akapity [00222]–[00225]) |
| [D6: EP3655531A1](https://patents.google.com/patent/EP3655531A1/en) | Kontrole dodawane przed izolacją EV i na późniejszych etapach oznaczania RNA (akapity [00220], [00223], [00226]) |
| [N1: Drees i współautorzy](https://pubmed.ncbi.nlm.nih.gov/38947877/) | Kontrola jakości oznaczania EV-miRNA z wykorzystaniem liposomów i kontroli kolejnych etapów procesu |

D5, D6 i N1 są szczególnie ważne, ponieważ podważają możliwość traktowania kilku kontroli jakości jako samodzielnego, nowego rozwiązania.

## 4. Wstępne porównanie cech

| Cecha | Szczególnie istotne ujawnienia |
| --- | --- |
| F1: osocze / in vitro | Częściowo lub w zbliżonym kontekście D1, D3–D6, N1 |
| F2: chip mikroprzepływowy do EV | D2 |
| F3: miR-21 i miR-155 | D1 |
| F4: referencyjne cząstki przed izolacją | D4, D5, D6, N1 |
| F5: RNA kontrolny na późnym etapie | D5, D6, N1 |
| F6: kontrola hemolizy | D3 |
| F7: ocena sygnałów kontroli jakości | D4–D6, N1 (w różnym zakresie) |
| F8: wstrzymanie wyniku | D3, D5; podobne rozwiązania w D4 i N1 |

Tabela zestawia tylko cechy potwierdzone lub częściowo odzwierciedlone w przeanalizowanych fragmentach. Brak wymienienia publikacji nie oznacza, że cecha nie została w niej ujawniona.

## 5. Nowość: art. 54 EPC

Dla wykazania braku nowości zasadniczo należy zidentyfikować pojedyncze wcześniejsze ujawnienie wszystkich cech określonego zastrzeżenia w tej samej kombinacji. W przeanalizowanych fragmentach źródeł nie potwierdzono identycznej konfiguracji wszystkich cech F1–F8. Wynik ten **nie potwierdza nowości**, ponieważ zakres przeglądu był ograniczony, a budowa hipotetycznego rozwiązania nie została dostatecznie doprecyzowana.

## 6. Poziom wynalazczy: art. 56 EPC

Jako punkt odniesienia można przyjąć publikację N1, obejmującą wieloetapową kontrolę jakości analizy EV-miRNA. EV-RNA Guard różni się od niej przede wszystkim przyjętym chipem, zestawem biomarkerów i sposobem komunikowania jakości wyniku.

Nie przedstawiono danych pozwalających przypisać tej kombinacji nieoczekiwaną poprawę dokładności ani identyfikacji źródła błędu. Obiektywny problem techniczny można zatem sformułować ostrożnie jako **opracowanie alternatywnego systemu analizy EV-miRNA z kontrolą jakości**.

Dokument D2 wskazuje układ mikroprzepływowy, D1 znane markery, D3 kontrolę hemolizy, a D4–D6 i N1 wcześniejsze rozwiązania kontroli procesu. W tym świetle połączenie znanych elementów może być oczywiste dla specjalisty. **Na podstawie dostępnego materiału nie wykazano poziomu wynalazczego.**

Dwie kontrole nie umożliwiają automatycznie dokładnej lokalizacji błędu. W uproszczonym modelu sygnał R-EV zależy od wychwytu, lizy, ekstrakcji, odwrotnej transkrypcji i PCR; sygnał R-POST przede wszystkim od późniejszych etapów RT i PCR. Jest to wyłącznie model poglądowy, nie wynik doświadczenia.

## 7. Przykładowe zastrzeżenia

Poniższy fragment ma charakter redakcyjnego ćwiczenia. Nie jest propozycją gotową do zgłoszenia.

**1.** System *in vitro* do analizy mikroRNA w próbce osocza, obejmujący mikroprzepływowy moduł wychwytu pęcherzyków pozakomórkowych z powierzchnią funkcjonalizowaną ligandem, moduł uwalniania i oczyszczania RNA, moduł oznaczania miR-21 i miR-155 oraz jednostkę przetwarzania danych, znamienny tym, że jest przystosowany do pomiaru (i) nieendogennego RNA z cząstek referencyjnych dodawanych do próbki przed wychwytem pęcherzyków oraz (ii) odrębnego nieendogennego RNA dodawanego po oczyszczeniu RNA, przed odwrotną transkrypcją, przy czym jednostka przetwarzania danych jest skonfigurowana do uwzględniania obu pomiarów i wskaźnika hemolizy przy wyznaczaniu ważności wyniku.

**2.** System według zastrz. 1, w którym ligandy wychwytujące obejmują aptamery wiążące marker powierzchniowy CD63.

**3.** System według zastrz. 1 albo 2, w którym oba nieendogenne RNA oznacza się z użyciem odrębnych zestawów starterów RT-qPCR.

**4.** System według któregokolwiek z zastrz. 1–3, w którym wskaźnik hemolizy obejmuje stosunek sygnału miR-451 do sygnału wybranego miRNA normalizującego.

**5.** System według któregokolwiek z zastrz. 1–4, w którym jednostka przetwarzania danych przypisuje oddzielne statusy niezgodności wczesnej kontroli odzysku i późnej kontroli reakcji RT-qPCR.

## 8. Pozostałe wymogi i dalsze działania

Art. 52 i 57 EPC wskazują na potrzebę określenia technicznego charakteru rozwiązania i jego przemysłowego zastosowania. Art. 53(c) EPC wymaga rozróżnienia metod diagnostycznych wykonywanych na ciele i badań *in vitro*. Z punktu widzenia art. 83 i 84 EPC konieczne byłoby opisanie materiałów kontrolnych, sposobu pomiaru, progów akceptacji i działania algorytmu w stopniu umożliwiającym realizację i wyznaczenie zakresu ochrony.

Gdyby hipotetyczną koncepcję rozwijano, należałoby przeprowadzić szersze wyszukiwanie, badania porównawcze z opublikowanymi rozwiązaniami, ocenić powtarzalność pomiarów, wpływ hemolizy oraz skuteczność identyfikacji błędów.

**Wniosek końcowy:** dostępne źródła pokazują liczne wcześniejsze ujawnienia elementów projektu. Nie potwierdzono ani nie wykluczono nowości dokładnej kombinacji, natomiast nie wykazano poziomu wynalazczego. EV-RNA Guard pozostaje wyłącznie przykładową koncepcją edukacyjną.

Pełny wykaz źródeł: [Patent-Sources.md](../references/Patent-Sources.md).
