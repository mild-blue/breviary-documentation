### Vypis Pacientu HEPARIN
- Vypise se seznam pacientu serazeny podle znaceni postele, pacienti bez takoveho udaje jsou serazeni abecedne.
- Vyhledavani pacientu je podle substringu, ne podle zacatku jmena/prijmeni, proto kdyz zadam napriklad L, nenajde to pouze pacienty od L ale vsechny pacienty s L ve jmene nebo prijmeni.
- Pacienti u kterych chybi informace nejsou tak vyrazne oznaceni a je u nich informace: “k zahajeni lecby chybi informace”, po rozkliknuti takoveho pacienta se objevi nova stranka, kde je mozne doplnit informace.
- U pacientu, u kterych zatim nebylo akceptovano doporuceni nebo manualne nastavena hodnota se ukazuje + doporuceni.
- U pacientu je vzdy udaj o poslednim doporucenem terminu dalsiho vyseteni, “za x hodin” nebo “pred x hodinami”.
<br/>
Test: upravte jmeno libovolneho pacienta, pote zkontrolujte, jestli se jeho jmeno upravilo i v seznamu pacientu.
