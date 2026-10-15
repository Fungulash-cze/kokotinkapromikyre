# Plán implementace: Potící se a zmenšující se tlačítko „NE“

Tento plán detailně popisuje vylepšení interakce tlačítka **„NE“**, které při každém úskoku viditelně panikaří, zmenšuje se a potí, a přitom si zachovává minimalistickou vizuální identitu CloseFriends.

---

## 1. Postupná progrese úskoků (Panika a zmenšování)

Při každém pokusu o chycení tlačítka se změní jeho stav:

- **1. skok (Lehká nervozita)**:
  - Měřítko (scale): **92 %**
  - Efekt: Odlétne jedna animovaná kapka potu (`💦` / elegantní minimalistická kapka)
  - Zvuk: Rychlý úskočný tón
- **2. skok (Stupňující se panika)**:
  - Měřítko (scale): **80 %**
  - Efekt: Tlačítko se lehce chvěje (nervózní jitter animace) a uvolní více kapek potu
  - Zvuk: Vyšší, nervóznější tón
- **3. skok (Totální vyčerpání)**:
  - Měřítko (scale): **68 %**
  - Efekt: Výraznější pot a zoufalé chvění
  - Zvuk: Komický vyčerpaný zvuk

---

## 2. Návrat domů a úleva

- Po 3. skoku se tlačítko na zlomek sekundy zastaví.
- Plynule doplachtí zpět na své původní místo v kartě.
- Při dosednutí se „nadechne“ a vrátí se na plnou velikost **100 %** (předstírá, že je v klidu a připravené k běžnému stisknutí).

---

## 3. Finální proměna v „Yessir“

- Jakmile se uživatel k odpočívajícímu tlačítku přiblíží kurzorem nebo se ho dotkne na mobilu:
  - Tlačítko okamžitě bez varování vyskočí do plné síly.
  - Text se promění v **„Yessir“**.
  - Získá styl hlavního tmavého tlačítka.
  - Kliknutí spustí konfety a vítěznou hlášku.

---

## 4. Dodržení minimalistického CloseFriends stylu

- Kapky potu a animace chvění budou realizovány čistým CSS bez rušivých prvků či grafického smetí.
- Zachová se stávající mint zelená paleta (`#6cbf8f`), inkoustová čerň (`#111613`) a čistá typografie.
- Resetovací tlačítko spolehlivě vrátí velikost i stav tlačítka na výchozí hodnoty.
