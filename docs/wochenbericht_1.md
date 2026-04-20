Semesterprojekt Wochenbericht: Neon Gravity Breakout

Berichtszeitraum:Woche 1 (13. April – 20. April)
Projektstatus:Anforderungsanalyse und Konzeptionelle Modellierung

1. Individueller Beitrag in dieser Woche
In der ersten Phase unseres Semesterprojekts habe ich mich intensiv mit der theoretischen Grundlegung und der Anforderungsanalyse für Neon Gravity Breakout beschäftigt.Da ein stabiles Systemdesign die Basis für eine effiziente Implementierung ist,lag mein Fokus darauf,die interaktionslogik zwischen den verschiedenen Systemkomponenten zu definieren.

Ein wesentlicher Teil meiner Arbeit war die Erstellung eines umfassenden UML-Aktivitätsdiagramms.Dieses Diagramm visualisiert den Kontrollfluss zwischen dem Spieler und der Game-Engine.Dabei habe ich besonders folgende Aspekte modelliert:

Die Verarbeitung von Benutzereingaben (Input-Handling) in Echtzeit.

Den Entscheidungsprozess der Engine bei Kollisionen zwischen Ball,Paddle und Blöcken.

Die Integration der Neon Gravity Logik,welche die physikalischen Parameter des Spiels dynamisch beeinflusst.

Zusätzlich zur Modellierung habe ich die funktionalen Anforderungen präzisiert,um sicherzustellen,dass grundlegende Features wie die Highscore-Verwaltung und die Spielzustandssteuerung (Menü, Aktiv, Pause, Game Over) von Anfang an im Design berücksichtigt werden.

2. Repository & Technische Analyse (Teil II)
Nach Erhalt des Repository-Links auf GitHub habe ich eine erste technische Bestandsaufnahme durchgeführt. Dabei habe ich festgestellt, dass das vom Lehrstuhl bereitgestellte Framework auf Java und libGDX basiert (ersichtlich an der Gradle-Struktur und den Core-Modulen).

Ich habe das Repository erfolgreich auf mein lokales System geklont und mich mit der Verzeichnisstruktur vertraut gemacht. Um die Dokumentation sauber vom Quellcode zu trennen, habe ich ein Verzeichnis docs/ angelegt, in dem ich das Aktivitätsdiagramm (project_behavior.svg) und diesen Wochenbericht hinterlegt habe. Ein erster Push in das Repository wurde erfolgreich durchgeführt.

3. Ausblick: Wie geht es weiter?
Nachdem die theoretische Interaktionslogik nun dokumentiert ist, wird der nächste Schritt die Einarbeitung in das libGDX-Framework sein. Mein Ziel für die kommende Woche ist es, die Architektur der bereitgestellten core-Klasse zu verstehen und die erste einfache Game-Loop zu implementieren, die ein Fenster öffnet und auf Basis meines Aktivitätsdiagramms einfache Eingaben entgegennimmt.