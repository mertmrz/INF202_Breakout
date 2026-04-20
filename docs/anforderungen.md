# Anforderungsanalyse: Neon Gravity Breakout

Im Rahmen der Planungsphase wurden folgende funktionale (F) und nicht-funktionale (NF) Anforderungen für das Spiel definiert:

### Funktionale Anforderungen
* **F01 (Spielersteuerung):** Der Spieler muss das Paddle am unteren Bildschirmrand über die Tastatur (Pfeiltasten oder A/D) flüssig auf der horizontalen Achse bewegen können.
* **F02 (Ballphysik):** Der Ball muss sich gemäß physikalischer Grundregeln (Einfallswinkel gleich Ausfallswinkel) verhalten und an den Bildschirmrändern (links, rechts, oben) sowie am Paddle korrekt abprallen.
* **F03 (Kollisionserkennung):** Das System muss Kollisionen zwischen dem Ball und den Blöcken (Bricks) in Echtzeit registrieren. Getroffene Blöcke müssen zerstört und dem Spieler Punkte gutgeschrieben werden.
* **F04 (Neon Gravity Mechanik):** Das Spiel muss eine spezielle Gravitations-Mechanik enthalten. Bestimmte Events oder Power-Ups verändern temporär die Gravitation (z.B. Ball wird nach unten oder oben gezogen), worauf der Spieler reagieren muss.
* **F05 (Spielstatus & Leben):** Wenn der Ball den unteren Bildschirmrand passiert, verliert der Spieler ein Leben. Sind alle Leben aufgebraucht, wechselt das System in den "Game Over"-Zustand.

### Nicht-Funktionale Anforderungen
* **NF01 (Performance):** Das Spiel muss flüssig mit konstant 60 FPS (Frames Per Second) laufen. Die Kollisionsberechnung darf keine spürbaren Verzögerungen (Lags) verursachen.
* **NF02 (Usability & State Machine):** Die Benutzeroberfläche muss intuitiv sein. Ein reibungsloser Wechsel zwischen den Spielzuständen (Main Menu -> In-Game -> Pause -> Game Over) muss über eine State Machine gewährleistet sein.
* **NF03 (Wartbarkeit):** Der Quellcode muss den objektorientierten Prinzipien entsprechen. Die Logik für Physik, Rendering und Input-Handling muss modular getrennt sein, um das libGDX-Framework optimal zu nutzen.