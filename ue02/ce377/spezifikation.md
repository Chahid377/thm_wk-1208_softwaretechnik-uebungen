# Anforderungen an den THM-Terminplaner

Mitwirkende: Chahid377

## 1. Allgemeine Beschreibung

Der THM-Terminplaner soll Studierenden ermöglichen, Termine bei Lehrenden online zu buchen. Lehrende können ihre verfügbaren Zeiten eintragen und das Sekretariat kann die Buchungen verwalten.

**Beispiel:** Ein Student möchte eine Frage zu seiner Klausur besprechen. Er sucht im Terminplaner nach einem freien Sprechstundentermin bei seinem Dozenten.

## 2. Funktionale Anforderungen

### 2.1 Termine erstellen

Lehrende sollen Termine mit Datum, Uhrzeit und Dauer anlegen und bei Bedarf ändern können.

**Beispiel:** Ein Dozent erstellt für Montag um 10:00 Uhr einen Sprechstundentermin mit einer Dauer von 30 Minuten.

### 2.2 Termine buchen

Studierende sollen freie Termine auswählen und verbindlich buchen können. Jeder Termin darf nur einmal vergeben werden.

**Beispiel:** Ein Student bucht den Termin am Montag um 10:00 Uhr. Anschließend wird dieser als belegt angezeigt und kann nicht erneut gebucht werden.

### 2.3 Termine absagen

Studierende sollen ihre Buchungen bis spätestens 24 Stunden vor dem Termin stornieren können. Lehrende sollen ihre angebotenen Termine ebenfalls absagen können.

**Beispiel:** Ein Student sagt seinen Termin zwei Tage vorher ab. Der Termin wird automatisch wieder für andere Studierende freigegeben.

### 2.4 Terminübersicht

Das Sekretariat soll die angebotenen und gebuchten Termine der zuständigen Lehrenden einsehen können.

**Beispiel:** Eine Sekretärin sieht, dass ein Dozent am Dienstag sechs Termine anbietet und vier davon bereits gebucht sind.

## 3. Nichtfunktionale Anforderungen

### 3.1 Benutzerfreundlichkeit

Der Terminplaner soll übersichtlich gestaltet und sowohl am Computer als auch auf dem Smartphone nutzbar sein.

**Beispiel:** Ein Student öffnet den Terminplaner auf seinem Handy und kann ohne zusätzliche Anleitung einen Termin buchen.

### 3.2 Datenschutz

Persönliche Informationen dürfen nur von berechtigten Personen eingesehen werden.

**Beispiel:** Ein Student sieht, dass ein Termin belegt ist, kann aber nicht erkennen, welcher andere Student ihn gebucht hat.

## 4. Benutzeroberfläche

Der Terminplaner soll eine Kalenderansicht besitzen, in der freie und belegte Termine unterschiedlich dargestellt werden.

**Beispiel:** Freie Termine werden grün und belegte Termine grau angezeigt. Studierende können auf einen freien Termin klicken, um ihn zu buchen.

## 5. Fehlerbehandlung

Das System soll ungültige Eingaben und doppelte Buchungen verhindern. Bei Fehlern soll eine verständliche Meldung erscheinen.

**Beispiel:** Zwei Studierende versuchen gleichzeitig, denselben Termin zu buchen. Nur die erste erfolgreiche Buchung wird gespeichert. Die andere Person erhält die Meldung „Dieser Termin ist bereits vergeben“.

## 6. Datenspeicherung

Alle Termine und Buchungen sollen dauerhaft gespeichert und dem jeweiligen Benutzerkonto zugeordnet werden.

**Beispiel:** Ein Student bucht am Montag einen Termin für Freitag. Wenn er sich am Mittwoch erneut anmeldet, wird seine Buchung weiterhin angezeigt.

## 7. Benutzerrollen und Berechtigungen

Der Terminplaner soll drei Benutzerrollen besitzen: Studierende, Lehrende und Sekretariate. Jede Rolle erhält unterschiedliche Berechtigungen.

**Beispiel:** Studierende können Termine buchen und stornieren. Lehrende können Termine anbieten und bearbeiten. Sekretariate können die Buchungen der zuständigen Lehrenden einsehen.
