CODEBUCH	
Codebuch-Stand vom 2022-12-21, erstellt von Franziska Weber und Timo Gotsch	
Edgelist und Nodelist sind seperat auf diesem GitHub-Repository aufgeführt.	

edgelist
from: definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort.
to: definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc.
relation: definiert die Beziehung der Akteure zueinander, codiert nach einzelnen Ziffern:
	1: Freunde
	2: Liebschaft
	3: Mitglied
	4: Kollegen
	5: Ratsmitglied
	6: Kabinettsmitglied
	7: Unterstützung
	
nodelist
id: eindeutige Identifikation jedes einzelnen Knotens (vertex), benutzt wurden die Initalien der Namen. Bei Personen zwei Buchstaben, bei Gruppierungen drei.
name: Name oder Bezeichnung des Knotens.
type: definiert die Unterscheidung zwischen Personen und Gruppierung.
	1: Person
	2: Gruppierung
sector: Beschreibung der Zugehörigkeit der Personen zu einem bestimmten gesellschaftlichem Feld, Fokus wurde auf die Rollenverteilung innerhalb der Reichsbürger-Szene nach deren geplanten Putsch gelegt
NA: definiert fehlende Werte, bei der Datenerhebung das Feld einfach leer lassen, R rechnet NAs (missing values) automatisch raus..
