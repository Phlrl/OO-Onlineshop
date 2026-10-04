Schwierige OO-Aufgabe: Online-Shop

Programmiere einen kleinen Online-Shop in C#.

Klassen

Produkt

Name
Preis
Lagerbestand

Methoden:

Verkaufe(int menge)
LagerbestandAnzeigen()

Kunde

Name
Kundennummer
Warenkorb

Methoden:

ProduktHinzufuegen(Produkt produkt, int menge)
ProduktEntfernen(Produkt produkt)
GesamtpreisBerechnen()
BestellungAufgeben()

Warenkorb

Liste der Produkte
Mengen der jeweiligen Produkte

Methoden:

Hinzufuegen(...)
Entfernen(...)
Gesamtpreis()
Anzeigen()

Bestellung

Kunde
Produkte
Gesamtpreis
Bestellnummer
Anforderungen

Dein Programm soll:

Mindestens 5 Produkte erstellen.
Mindestens 2 Kunden erstellen.
Kunden Produkte in den Warenkorb legen lassen.
Die Menge eines Produkts berücksichtigen.
Produkte wieder aus dem Warenkorb entfernen können.
Den Gesamtpreis berechnen.
Beim Bestellen prüfen, ob genug Produkte auf Lager sind.
Nach einer erfolgreichen Bestellung den Lagerbestand reduzieren.
Eine Bestellung mit einer eindeutigen Bestellnummer erstellen.
Die Bestellung anschließend anzeigen.
Extra schwer

Baue ein Rabatt-System ein:

Unter 50 € → kein Rabatt
Ab 50 € → 5 %
Ab 100 € → 10 %
Ab 200 € → 15 %

Der Rabatt soll nicht direkt im Warenkorb gespeichert, sondern beim Berechnen des Endpreises berücksichtigt werden.

Regel: Versuch, private, public, Properties, Methoden, List<>, Konstruktoren und Objekte sinnvoll einzusetzen. Keine statischen Variablen für den kompletten Shop.