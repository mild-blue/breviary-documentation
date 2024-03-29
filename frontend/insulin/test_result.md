### Testování pridani noveho vysledku testu.
1. Vytvorte noveho inzulinoveho pacienta s libovolnym jmenem a hodnotami:
- Cilova glykemie = 7 mmol/l
- Celkova denni davka inzulinu (TDDI) = 20 jedn 
- Denni bazalni davka inzulinu = 15 jedn
- Typ inzulinu = Apidra
2. Zahajit inzulinovou lecbu.
3. Pridat novy vysledek tesu:
<br/>
Poznamka: testy provadejte hned za sebou. Po pridani vysledku testu neakceptujte doporuceni ani nenastavujte vlastni hodnotu. Klikejte "Pridat novy vysledek testu".

| Typ testu             | Vstup                                    | Vystup                                                                                                                                                                                         |
|-----------------------|------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Vysoka glykemie (>15) | Aktualni glykemie: 20<br/>Sacharidy: 10  | Doporucena davka: 3 jedn.<br/> Varovani: Validace lekare nutna. Hodnota glykémie (20 mmol/l) je vyšší než 15. Okamžitě zavolejte lékaře.                                                       |
| Glykemie 12,01-15     | Aktualni glykemie: 13<br/>Sacharidy: 20  | Doporucena davka: 2 jedn.<br/> Varovani: Konzultace lekare doporucena. Hodnota glykémie (13 mmol/l) je vyšší než 12. Pacienta pozorujte a znovu glykémii zkontrolujte nejpozději za 2 hodiny.  |
| Glykemie 4-12         | Aktualni glykemie: 8<br/>Sacharidy: 20   | Doporucena davka: 1,5 jedn.                                                                                                                                                                    |
| Glykemie 3-3,99       | Aktualni glykemie: 3,5<br/>Sacharidy: 20 | Doporucena davka: 0,5 jedn.<br/> Varovani: Konzultace lekare doporucena. Hodnota glykémie (3.5 mmol/l) je nižší než 4. Pacienta pozorujte a znovu glykémii zkontrolujte nejpozději za 30 minut. |
| Nizka glykemie (<3)   | Aktualni glykemie: 2<br/>Sacharidy: 20   | Doporucena davka: 0 jedn.<br/> Varovani: Validace lekare nutna. Hodnota glykémie (2 mmol/l) je nižší než 3. Okamžitě zavolejte lékaře.                                                         |

### Testovani hlasky "Riziko hypoglykemie"
1. Otevrte pacienta, ktereho jste vytvorili pri [testování pridani noveho vysledku testu.](test_result.md)
2. Otevrte historii pacientu, zkontrolujte, ze on nedostal zadnou davku (ve sloupci Davka musime videt "-" naproti kazdemu testu).
3. Kliknete "Pridat novy vysledek testu".
- Aktuální glykemie: 4,1
- Očekávaný příjem sacharidů: 0
4. Mela by se objevit hlaska " KONZULTACE LÉKAŘE DOPORUČENA.
   Riziko hypoglykémie. Zvažte příjem sacharidů (10 gramů)."