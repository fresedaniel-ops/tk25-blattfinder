# TK25-Blattfinder

Ermittelt aus WGS84-Koordinaten (z. B. Handy-GPS oder Google Maps) das Blatt der
Topographischen Karte 1:25 000 (TK25) mit Nummer, Blattnamen, Blattrahmen und Randwarnung.

- 2.984 Blätter bundesweit, Namen nach der tegeo-Liste „Baustelleninfos“, ergänzt aus den Blattübersichten der Länder
- „Meine Position“ nutzt das GPS des Geräts (nur über https, z. B. GitHub Pages)
- Blattsuche nach Nummer oder Name, Stapelverarbeitung mehrerer Punkte, CSV-Export
- Feld „Für das Messprotokoll“ passend zum Formular Baustelleninfos (B14 TK Karte, B15 Longitude/Ost, B16 Latitude/Nord);: TK25-Nummer, Name, Rechts-/Hochwert (ETRS89/UTM 32/33, DHDN/Gauß-Krüger 2–5), Koordinatensystem und WGS84-Breite/-Länge einzeln kopierbar
- Adresssuche über OpenStreetMap (Nominatim), nur in Deutschland
- Koordinaten per Adresse übergeben: `?c=52.6256,10.0817`

Blattschnitt: 10′ Länge × 6′ Breite, Zeile 01 ab 55°54′ N, Spalte 01 ab 5°50′ E.
Alles läuft im Browser, es werden keine Daten an einen Server gesendet.

tegeo – Tegtmeyer Geophysik GmbH
