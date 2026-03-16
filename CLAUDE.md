# MaManual – Projektregeln für Claude

## Was ist dieses Projekt?
Eine single-file PWA (index.html) mit eingebettetem CSS und JS.
Gehostet auf GitHub Pages unter mettbroetchen/mamanual.
Zielgruppe: nicht-technische Nutzer (Mutter).

## Sprachen
- UI-Sprachen: Deutsch, Spanisch, Englisch
- Alle neuen Anleitungen müssen in allen 3 Sprachen vorhanden sein

## Regeln
- Alles bleibt in einer einzigen index.html Datei
- Kein Build-Prozess, kein Node, kein npm
- CSS und JS sind direkt in der HTML eingebettet
- Neue Geräte/Anleitungen nach dem bestehenden Muster hinzufügen
- Nach Änderungen: HTML-Validität sicherstellen

## Typischer Task
"Füge eine Anleitung für [Gerät] hinzu" → Claude erstellt Branch, 
bearbeitet index.html, öffnet PR zur Review.
