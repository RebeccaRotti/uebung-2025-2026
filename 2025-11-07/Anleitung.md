Lernziele
	•	HTML-Grundstruktur verstehen (Doctype, Head, Body, grundlegende Tags)
	•	Erste Formatierungen mit CSS anwenden (Farben, Schriftarten, Selektoren, Kaskade)
	•	Zusammenspiel von HTML (Inhalt) und CSS (Gestaltung) erleben

⸻

Ablauf

Schritt 1 – HTML-Grundgerüst erstellen

Gemeinsam im WebStorm ein neues HTML-Dokument anlegen:

<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <title>Meine erste Webseite</title>
</head>
<body>
  <h1>Willkommen auf meiner ersten Webseite!</h1>
  <p>Dies ist mein erster Absatz mit etwas Text.</p>
  <a href="https://www.fh-ooe.at/">Zur FH-Website</a>
</body>
</html>

👉 Besprechen: Doctype, Head/Meta, Struktur, Tags (h1, p, a).

⸻

Schritt 2 – CSS einbinden

Externes Stylesheet anlegen: style.css

body {
  font-family: Arial, sans-serif;
  background-color: #f9f9f9;
}

h1 {
  color: darkblue;
}

p {
  color: #333;
}
a {
  color: green;
  text-decoration: none;
}
a:hover {
  color: red;
}
p {
  color: red;
}

👉 Besprechen: Selektoren, Eigenschaften, Werte, Pseudoklasse :hover.

⸻

Schritt 3 – Erweiterung durch Studierende

Die Studierenden sollen die Seite anpassen:
	•	Eine zweite Überschrift (h2) hinzufügen
	•	Ein Bild (<img>) einfügen
	•	Einen Button oder Link gestalten (z. B. als „Button-Look“ mit CSS)
	•	Hintergrundfarbe oder Schriftart ändern

⸻

Diskussionspunkte (im Plenum)
	•	Unterschied Inhalt (HTML) vs. Gestaltung (CSS)
	•	Inline vs. externes CSS (warum extern besser ist)
	•	Kaskadierung & Reihenfolge der Regeln

⸻

👉 Ergebnis: Jede*r Studierende hat am Ende eine eigene Mini-Webseite mit Basis-HTML und einfachem CSS – und sie verstehen das Zusammenspiel beider Sprachen.

⸻

Soll ich dir die Übung gleich als foliengeeignete Schritt-für-Schritt-Anleitung aufbereiten, sodass du sie direkt in deine Präsentation übernehmen kannst?