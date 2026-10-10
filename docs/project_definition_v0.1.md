# Civitas – Projektdefinition v0.1

Civitas ist ein Open-Source-Spiel, das Wirtschafts- und Transportaufbau mit einer begehbaren 3D-Welt verbindet. Im Zentrum steht der Aufbau von Industrie, Produktion und Vertriebsnetzen. Ergänzt wird das durch Farming und weitere Tätigkeiten, die der Spieler aus der First-Person-Perspektive erlebt. Das Spiel nutzt feste Karten und soll langfristig durch eine Community erweitert werden können.

## Ziel der ersten Version

Die erste Version ist bewusst klein gehalten. Sie soll eine einfache 3D-Welt, einen begehbaren Charakter, eine grundlegende Kamera- und Bewegungssteuerung und eine saubere Projektstruktur enthalten. Komplexe Wirtschaftssysteme, Fahrzeuge, Farming, Modding und Multiplayer sind ausdrücklich nicht Teil dieser ersten Version.

## Technik

Das Spiel entsteht in Godot 4. Als Skriptsprache wird GDScript verwendet, weil es der einfachste und direkteste Weg in Godot ist. Spiel- und Konfigurationsdaten werden vorerst in JSON gespeichert. Modding wird aktuell nicht umgesetzt, die Projektstruktur soll spätere Erweiterungen aber nicht verbauen.

## Arbeitsweise

Alle Entscheidungen entstehen im Mainchat nach dem Muster Entwurf, Review, Freigabe. Die Dokumentation liegt im Ordner docs, das Godot-Projekt im Ordner game. Weitere Arbeitsbereiche werden erst eröffnet, wenn die Basis steht und sich das Projekt als tragfähig zeigt.

## Nächste Schritte

Als Nächstes wird das Git-Repository initialisiert und das Godot-Projekt im Ordner game angelegt. Danach entstehen eine einfache Welt und der erste spielbare Charakter.