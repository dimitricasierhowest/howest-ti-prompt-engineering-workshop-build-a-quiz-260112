

### Doel

Ontwerp en implementeer een **Single Page Application (SPA)** voor het **periodiek systeem der chemische elementen**, waarmee gebruikers elementen kunnen **verkennen, zoeken en in detail bekijken**.

### Technologie

Gebruik uitsluitend:

* **HTML**
* **CSS**
* **Vanilla JavaScript**

❌ Geen externe libraries, frameworks of build tools.

---

### Databron

* Gebruik de afbeelding **tabel.png** als **enige bron voor alle elementgegevens**.
* Zet de gegevens uit deze tabel om naar een **gestructureerde JavaScript-datastructuur** (bijv. array van objecten).
* Alle getoonde informatie in de app moet uit deze dataset afkomstig zijn.

---

### Functionele eisen

#### Periodiek systeem

* Toon het **klassieke Mendelejev-periodiek systeem** in **tabelvorm**.
* De positionering van de elementen moet overeenkomen met:

  * groepen
  * perioden
  * lege ruimtes waar van toepassing

#### Interactie

* Bij **klik op een element**:

  * wordt **geen nieuwe pagina geladen**
  * verschijnt een **detailweergave binnen dezelfde pagina**
  * toon **alle beschikbare gegevens** van het geselecteerde element
    (bijv. naam, symbool, atoomnummer, soort, toestand, enz.)

#### Zoek- en filterfunctionaliteit

Implementeer een zoekfunctie waarmee gebruikers kunnen filteren op:

* **Naam**
* **Symbool**
* **Atoomnummer**
* **Soort** (bijv. metaal, niet-metaal, edelgas)
* **Toestand** (vast, vloeibaar, gas)

Zoekresultaten moeten:

* direct zichtbaar zijn
* het periodiek systeem dynamisch updaten

---

### Vormgeving & UI

* Gebruik de **visuele stijl van de IMDb-website**, zoals in de meegeleverde screenshot:

  * donkere achtergrond
  * gele accentkleuren
  * duidelijke, moderne typografie
  * kaart-/paneelachtige lay-out voor detailweergave
* Zorg voor een **overzichtelijke en consistente UI**
* Interacties (hover, selectie, openen detailpaneel) moeten **soepel en intuïtief** aanvoelen

---

### Technische eisen

* Alles werkt binnen **één HTML-bestand** (SPA-structuur)
* Logische scheiding tussen:

  * data
  * DOM-manipulatie
  * interactielogica
* Efficiënte rendering (geen onnodige DOM-herbouw)
* Goed leesbare en onderhoudbare code

---

### Resultaat

* Eén zelfstandig HTML-bestand dat direct in de browser werkt
* Volledig functioneel zonder externe afhankelijkheden
* **Gebruiksvriendelijk, performant en visueel consistent**
* Geschikt als leerapplicatie of interactieve demonstratie

