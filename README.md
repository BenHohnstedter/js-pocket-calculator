# js-pocket-calculator

Ein kompakter Taschenrechner, komplett in HTML, CSS und JavaScript – ohne Bibliotheken oder Build-Tools. Die geöffnete Datei im Browser genügt, nichts muss installiert werden.

## Funktionen

- Grundrechenarten (+ , -, *, /)
- Potenzierung (^) und Modulo (%)
- Dezimalkomma
- Löschen der letzten Eingabe und komplettes Zurücksetzen
- Anzeige der aktuellen Eingabe und des Ergebnisses an einer Stelle
- Responsive Darstellung, funktioniert auf Desktop und Smartphone

## Technologien

- HTML5
- CSS (eigenes Design, Google-Font-Tilt-Neon)
- Vanilla JavaScript (kein Framework)

## Starten

Einfach `index.html` im Browser öffnen – oder unter XAMPP:

**Lokal erreichbar unter:** `http://localhost/pu-js-pocket-calculator/`

## Struktur

```
index.html   – Oberfläche und Rechenlogik (eval-basiert)
css/         – Styles
```

## Hinweis

Die Rechnung wird direkt über `eval()` ausgewertet – bewusst einfach gehalten als Trainingsprojekt für DOM- und Event-Handling. Für produktiven Einsatz wäre ein expliziter Parser sinnvoller.

## Projektbezug

Übung für semantisches DOM-Handling und `onclick`-Event-Verarbeitung in reinem JavaScript.