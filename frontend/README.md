### Testovani Breviary
Toto jsou podklady pro testovani aplikace Breviary.
Nize je popis pro pripravu prostredi a pak rozcestnik na jednotlive testovaci scenare.

Pokud chcete pridat novy scenar:
1. Vytvorte file ve slozce "frontend/heparin" nebo "frontend/insulin" (v zavislosti na tom pro jaky lek testujete).
2. Pojmenujte ho "name.md" (namisto "name" napiste nazev testu, ktery vymyslite).
3. Ve filu popiste postup provedeni testu, inspirujte se [grafem pro inzulin](https://app.diagrams.net/#Hmild-blue%2Fbreviary-backend%2F802_tests_summarization%2Fdocumentation%2Fdiagrams_en%2Finsulin-flow-chart.drawio.xml) nebo [grafem pro heparin](https://app.diagrams.net/#Hmild-blue%2Fbreviary-backend%2F802_tests_summarization%2Fdocumentation%2Fdiagrams_en%2Fheparin-flow-chart.drawio.xml).
4. Pridejte odkaz na file do rozcestniku. Navod jak pridat odkaz na file [zde](https://www.jetbrains.com/help/webstorm/markdown.html).


### iOS instalace beta-verze
1. Nainstaluj si poslední verzi aplikace z [TestFlight](https://developer.apple.com/testflight/)
    - je nutné být přidán jako beta-tester v App Store Connect, v případě, že aplikaci nevidíš kontaktuj Nasťu nebo Ľuboše

### Android instalace beta-verze
1. Na [Google Play](https://play.google.com/) vyhledej aplikaci `Virtual Breviary`
2. Na stránce aplikace zoskroluj dole a zaklikni tlačítko `Join` v sekci `Join the beta`
    - občas se stane, že trvá pár (desítek) minut než se objaví tlačítko update, v tom připade je možné zajít do `manage apps & devices` skryté pod profilovou ikonkou kde by se po kliknutí na `Virtual Breviary` mnělo ukázat tlačítko update
3. Odinstaluj si produkční verzi aplikace
4. Nainstaluj si poslední beta verzi aplikace

### Login do aplikace
1. Po otevření tě aplikace vyzve k vybrání organizace. Klikni na tlačítko `Přidat vlastní`.
2. Do pole `Název organizace` napiš `stg` (ale může to být cokoliv)
3. Do pole `Adresa serveru` napiš `https://breviary.stg.mild.blue/` (adresu stagingu)
4. Vyber organizaci `stg` a klikni na `Pokračovat do organizace stg`
5. Po úspěšném připojení klikni na `Přihlásit se`. Pokud nedošlo k úspěšnému připojení byla buď chybně zadaná adresa nebo stg neběží. Vyzkoušej zadáním adresy do tvého oblíbeného prohlížeče.
6. Zadej uživatelské jméno a heslo pro `stg`. (najdeš v bitwardenu)
7. Vyber hospitalizační jednotku default
8. Vyber typ léku `Heparin` nebo `Inzulin` v zavislosti na testovacim scenari.

### Testovaci scenare
#### Heparin:
1. [Testovani vypisu pacientu.](heparin/patient_list.md)
2. [Testovani notifikací.](heparin/notification.md)
3. [Testovani hlasek "Není možné doporučit dávku, protože pacientovo cílové aPTT ratio je mimo rozsah nomogramu" a "Není možné doporučit dávku, protože pacientova hmotnost je mimo rozsah nomogramu".](heparin/weight_aptt.md)
4. [Testovani nouzoveho zastaveni.](heparin/emergency_stop.md)
5. [Testovani nizkeho aptt ratio.](heparin/weight_aptt.md)
6. [Testovani pri rychlosti pumpy 0.](heparin/pump_speed0.md)
#### Inzulin:
1. [Testovani hlasky "Včera nebyla aplikována žádná dávka inzulínu".](insulin/no_insulin_yesterday.md)
2. [Testovani pridani noveho vysledku testu.](insulin/test_result.md)
3. [Testovani hlasky "Riziko hypoglykemie".](insulin/test_result.md)
4. [Edge case.](insulin/cases.md)
5. [Real life case.](insulin/cases.md)