# Phasenplan: Terminplaner für die THM

Kürzel: ce377

## Studie

**Ergebnis:** Bewertete Lösungsalternativen und ein Projektvorschlag mit Aufwandsschätzung und Meilensteinplan als Entscheidungsgrundlage.

- Eigenentwicklung, Anpassung einer Open-Source-Lösung und Kauf nebeneinanderstellen und nach Kosten und Nutzen bewerten
- Die heutige Lage aufnehmen: wie Sprechstunden und Prüfungstermine bisher vereinbart werden und wo es hakt
- Aufwand schätzen und einen Meilensteinplan vorschlagen

## Systemspezifikation

**Ergebnis:** Abgestimmte Beschreibung der fachlichen Anforderungen, Abläufe, Daten und äußeren Schnittstellen sowie Testfälle zur Prüfung des vereinbarten Verhaltens.

- Mit Lehrenden und Sekretariaten Schritt für Schritt beschreiben, wie ein Sprechstundentermin gebucht wird
- Festlegen, welche Vorgänge ein KI-Agent über die API auslösen darf – z.B. freie Termine abfragen und buchen, aber keine Prüfungstermine absagen
- Bildschirmskizzen der Buchungsseite mit Studierenden durchgehen
- Festlegen, welche Angaben zu einem Termin gehören und wie Termine, Personen und Räume zusammenhängen
- Beschreiben, welche Termindaten mit dem Kalendersystem der Hochschule ausgetauscht werden
- Testfälle formulieren, an denen sich später zeigt, ob das System leistet, was vereinbart wurde

## Systemkonstruktion

**Ergebnis:** Technischer Entwurf mit Komponenten, ihren Schnittstellen, Technologieauswahl und Reihenfolge des Komponentenbaus.

- Das System in Komponenten zerlegen – z.B. Terminverwaltung, Benachrichtigung, Anmeldung – und deren Schnittstellen festlegen
- Datenbank, Programmiersprache und Web-Framework auswählen
- Die API entwerfen: Endpunkte, Datenformat und die Anmeldung der KI-Agenten festlegen
- Mit einem technischen Prototyp prüfen, ob die Anmeldung über das Hochschulkonto funktioniert
- Festlegen, in welcher Reihenfolge die Komponenten gebaut werden und welche Zwischenziele gelten

## Implementierung

**Ergebnis:** Programmierte und einzeln getestete Komponenten.

- Die Komponente „Benachrichtigung“ programmieren
- Die fertige Komponente „Terminverwaltung“ für sich testen, ehe sie mit anderen zusammenkommt

## Integration & Einführung

**Ergebnis:** Zusammengeführtes und als Ganzes getestetes System, das vom Auftraggeber abgenommen und in Betrieb genommen wurde.

- Die THM installiert das System in ihrer eigenen Umgebung und prüft es in eigener Verantwortung
- Terminverwaltung und Benachrichtigung zusammenführen und ihr Zusammenspiel gegen Testfälle prüfen
- Das System als Ganzes unter Federführung des Qualitätsbeauftragten gegen die Testfälle prüfen
- Mit einem KI-Agenten prüfen, ob sich ein Sprechstundentermin vollständig über die API buchen lässt
- Probebetrieb mit einem Fachbereich, ehe die ganze Hochschule umsteigt

## Wartung

**Ergebnis:** Im Betrieb betreutes, korrigiertes und um neue Anforderungen erweitertes System; Wartung ist eine fortlaufende Tätigkeit.

- Einen Fehler bei der Zeitumstellung beheben, den ein Sekretariat gemeldet hat
- Eine Hotline für Fragen der Anwenderinnen und Anwender besetzen
- Eine Warteliste für ausgebuchte Termine nachrüsten, die sich die Lehrenden nach einem Semester wünschen

## Abwägungen bei mehrdeutigen Zuordnungen

- **Bildschirmskizzen:** Systemspezifikation, weil die Abstimmung mit Studierenden Anforderungen an die Bedienung klärt; die technische Umsetzung der Oberfläche gehört dagegen zur Konstruktion und Implementierung.
- **Technischer Prototyp:** Systemkonstruktion, wenn er den konkreten Anmeldeentwurf überprüft; zur Studie gehört er, wenn zunächst die grundsätzliche Machbarkeit geklärt werden soll.
- **API:** Die erlaubten fachlichen Vorgänge gehören zur Spezifikation, während der konkrete technische Schnittstellenentwurf hier der Systemkonstruktion zugeordnet wird.
- **Testfälle:** Die Formulierung der fachlichen Testfälle gehört bereits zur Spezifikation, obwohl die entsprechenden Tests erst am realisierten System ausgeführt werden.
- **Hotline:** Wartung bei dauerhafter Unterstützung im Betrieb; eine nur während des Starts angebotene Hotline wäre auch der Einführung zuzuordnen.
- **Planung:** Die erste Aufwandsschätzung gehört hier zur Studie, während die technische Baureihenfolge zur Konstruktion gehört; beide Planungen können im Projektverlauf angepasst werden.
