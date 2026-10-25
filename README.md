# TK25-Blattfinder

Ermittelt aus WGS84-Koordinaten (z. B. Handy-GPS oder Google Maps) das Blatt der
Topographischen Karte 1:25 000 (TK25) mit Nummer, Blattnamen, Blattrahmen und Randwarnung.

- 2.954 Blätter bundesweit, Namen aus den Blattübersichten der Länder
- „Meine Position“ nutzt das GPS des Geräts (nur über https, z. B. GitHub Pages)
- Blattsuche nach Nummer oder Name, Stapelverarbeitung mehrerer Punkte, CSV-Export
- Adresssuche über OpenStreetMap (Nominatim), nur in Deutschland
- Koordinaten per Adresse übergeben: `?c=52.6256,10.0817`

Blattschnitt: 10′ Länge × 6′ Breite, Zeile 01 ab 55°54′ N, Spalte 01 ab 5°50′ E.
Alles läuft im Browser, es werden keine Daten an einen Server gesendet.

tegeo – Tegtmeyer Geophysik GmbH
