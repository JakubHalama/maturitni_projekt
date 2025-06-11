# MiniStrava

MiniStrava je jednoduchá webová aplikace pro sledování sportovních aktivit (běh, kolo, chůze). Cílem projektu je vytvořit přehledný a funkční sportovní tracker na úrovni střední školy.

---

## Obsah projektu

- **index.html** – hlavní stránka aplikace s formulářem a historií aktivit
- **Tailwind CSS** – použitý pro rychlé a moderní stylování přes CDN
- **app.js** – JavaScriptová logika pro ukládání, načítání a zobrazení aktivit pomocí `localStorage`

---

## Postup práce

### Fáze 1: Základní funkčnost
- Vytvoření HTML šablony s formulářem pro přidání nové aktivity
- Nastavení Tailwind CSS pro hezký a responzivní design
- Implementace ukládání dat do `localStorage`
- Zobrazení historie aktivit pod formulářem
- Možnost mazání jednotlivých aktivit

### Fáze 2: Statistiky a analýzy
- Výpočet celkové vzdálenosti a průměrné délky aktivity
- Filtrování aktivit podle typu (běh, kolo, chůze)
- Zobrazení základních statistik na hlavní stránce

### Fáze 3: Grafy a export dat
- Implementace grafů pomocí knihovny Chart.js pro vizualizaci výkonu
- Přidání možnosti exportu aktivit do CSV souboru
- Možnost importu dat pro zálohu a obnovení

### Fáze 4: Uživatelský komfort
- Přidání temného/světlého režimu (dark mode)
- Implementace jednoduchého přihlášení/fake login systému
- Vylepšení UI/UX, validace formulářů, notifikace

---

## Jak používat

1. Otevři `index.html` ve webovém prohlížeči.
2. Přidej novou aktivitu pomocí formuláře (vyber typ, zadej vzdálenost, délku, datum a poznámku).
3. Sleduj historii všech přidaných aktivit.
4. Klikni na „X“ u aktivity pro její odstranění.

---

## Technologie

- HTML5
- Tailwind CSS (CDN)
- JavaScript (ES6+)
- `localStorage` pro perzistentní ukládání dat
- [Chart.js](https://www.chartjs.org/) (plánováno pro budoucí grafy)

---

## Instalace a spuštění

Projekt je čistě frontendový, není potřeba žádný backend ani server.

Stačí stáhnout nebo naklonovat repozitář a otevřít `index.html` v libovolném moderním prohlížeči.

```bash
git clone https://github.com/uzivatel/ministrava.git
cd ministrava
# otevři index.html v prohlížeči
