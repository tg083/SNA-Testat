

# Datensatz Reichsbürger-Razzia 
# Codebuch-Stand vom 2022-12-21, erstellt von Franziska Weber und Timo Gotsch								

# Edgelist und Nodelist sind seperat auf diesem GitHub-Repository aufgeführt.																									

Das Netzwerk ist ein *ungerichtetes two-mode Akteursnetzwerk*. 

# EDGE-Attribute
#	Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).																								


**from**
definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort.

**to**
definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. 																								

**weight**  
Beziehungsstärke aufgrund der Nennung in den Fragen)  
3 = sehr starke Beziehung (erste Nennung),   
1 = starke Beziehung vorhanden (zweite Nennung)

**relation**
definiert die Beziehung der Akteure zueinander, codiert nach einzelnen Ziffern:																								 
1 = *Freunde*   
2 = *Liebschaft* 
3 = *Mitglied* 
4 = *Kollegen*
5 = *Ratsmitglied*
6 = *Kabinettsmitglied*
7 = *Unterstützung*

 
 
# NODE-Attribute  
# Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.																								  
**id**  
eindeutige Identifikation jedes einzelnen Knotens (vertex), benutzt wurden die Initalien der Namen. Bei Personen zwei Buchstaben, bei Gruppierungen drei. 																								
**name**
Name oder Bezeichnung des Knotens. 																								

**type**
Definiert die Unterscheidung zwischen Personen und Gruppierung.																								
1 = *Person*   
2 = *Gruppierung* 

**sector**    
sector	Beschreibung der Zugehörigkeit der Personen zu einem bestimmten gesellschaftlichem Feld, Fokus wurde auf die Rollenverteilung innerhalb der Reichsbürger-Szene nach deren geplanten Putsch gelegt

**NA**  
NA	definiert fehlende Werte, bei der Datenerhebung das Feld einfach leer lassen, R rechnet NAs (missing values) automatisch raus..																								 

