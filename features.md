# Features – Die Taverne

1. Startbildschirm mit Titel, kurzer Einleitung und Spielziel.
2. Hilfe-Befehl (`hilfe`), der alle verfügbaren Befehle auflistet.
3. Fünf Räume (Schankraum, Küche, Keller, Gästezimmer, Hof) mit eigener Beschreibung.
4. Bewegung zwischen Räumen mit `gehe norden/süden/osten/westen`.
5. Raum ansehen mit `schau`: zeigt Beschreibung, Ausgänge und Gegenstände.
6. Gegenstände aufnehmen (`nimm <gegenstand>`) und ablegen (`lege <gegenstand>`).
7. Inventar mit fester Größe (Array, max. 5 Plätze) und Befehl `inventar`.
8. Verschlossener Keller: nur mit Kerze betretbar (sonst zu dunkel).
9. Gespräch mit dem Wirt (`rede wirt`), der je nach Inventar einen Hinweis gibt.
10. Rätsel: Der Wirt tauscht den Schlüssel gegen einen Gegenstand aus der Küche.
11. Zugzähler: Jeder Befehl zählt als Zug, am Ende wird die Anzahl angezeigt.
12. Siegbedingung: Haustür im Schankraum mit dem Schlüssel öffnen (`öffne tür`).
13. Ungültige Eingaben werden abgefangen und mit einer Fehlermeldung beantwortet.
14. Spiel jederzeit mit `beenden` verlassen.
