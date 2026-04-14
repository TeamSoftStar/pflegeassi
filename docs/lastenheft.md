# Lastenheft

    Projektbezeichnung      PflegeAssi
    Projektleitung          Tim Klein
    Erstellt am             08.04.2026
    Letzte Änderung am
    Status                  in Bearbeitung
    Aktuelle Version        1.0
    Änderungsverlauf
        Nr.     Datum           Version         Geänderte Kapitel           Art der Änderung            Verantwortlich      Status
        --------------------------------------------------------------------------------------------------------------------------
        1       08.04.2026      1.0             Alle                        Erstellung                  B.Maaßen             -   
        2
        3


# Inhalt

    1 Einleitung
    2 Allgemeines
        2.1 Ziel und Zweck des Dokuments
        2.2 Ausgangssituation
        2.3 Projektbezug
        2.4 Abkürzungen
        2.5 Verteilung und Freigabe
    3 Konzept
        3.1 Ziel(e) der Anbieter
        3.2 Ziel(e) und Nutzen der Anwender
        3.3 Zielgruppe(n)
    4 Funktionale Anforderungen
        4.1 Anforderung 1
        4.2 Anforderung 2
        4.3 Anforderung 3
        4.4 Anforderung 4
    5 Nichtfunktionale Anforderungen
        5.1 Allgemeine Anforderungen
        5.2 Gesetzliche Anforderungen
        5.3 Technische Anforderungen
    6 Lieferumfang
        6.1 Lieferumfang
        6.2 Kosten
        6.3 Liefertermin
        6.4 Ansprechstelle und Lieferort
    7 Abnahmevoraussetzungen
    8 Anhang


# 1 Einleitung

    Das vorliegende Lastenheft enthält die an das zu entwickelnde Produkt gestellten funktionalen sowie nicht-funktionalen Anforderungen. Es dient als Basis für die Ausschreibung und Vertragsgestaltung und bildet somit die Vorgabe für die Angebotserstellung. Kommt es zwischen SoftStar und Becker Pflege & Betreuung zu einem Vertragsabschluss, ist das bestehende Lastenheft rechtlich bindend.
    Mit den Anforderungen werden die Rahmenbedingungen für die Entwicklung festgelegt, die von dem Auftragnehmer im Pflichtenheft detailliert ausgestaltet werden.


# 2 Allgemeines

    2.1 Ziel und Zweck des Dokuments
        Dieses Lastenheft beschreibt eine Software für die Dokumentation der Firma „Becker Pflege & Betreuung“

    2.2 Ausgangssituation
        Herr Becker möchte für seine Mitarbeiter eine papierlose Dokumentation zur Entlastung und besseren Dokumentation und Durchführung von Medikamentenverwaltung, Dienstplan Dokumentation und Patientenverwaltung.
        Die Software dient zur Automatisierung und Fehlervermeidung der genannten Punkte. 
        Mitarbeiter sollen so entlastet werden.

    2.3 Projektbezug
        Das vorliegende Projekt ist ein unabhängiges Projekt und soll so erstellt werden, dass in der Zukunft gegebenenfalls Erweiterungen oder Änderungen vorgenommen werden können.

    2.4 Abkürzungen
        NFC: Near Field Communication - Ist ein internationaler Funkstandard zur drahtlosen Datenübertragung über kurze Strecken, meist wenige Zentimeter.

        z.B: Zum Beispiel

        Bzw.: Beziehungsweise Pop-Up: Grafisches Fenster, das plötzlich über der aktuellen Webseite erscheint Informationen oder Formulare anzuzeigen.
        
        MFA: Die Multi-Faktor-Authentifizierung (MFA) ist ein Sicherheitsverfahren, das von Nutzern zwei oder mehr unterschiedliche Nachweise (Faktoren) zur Bestätigung ihrer Identität verlangt und einen besseren Schutz als Passwörter allein bietet.

    2.5 Verteilung und Freigabe
        Rolle                    Name                   Telefon                   E-Mail                     Bemerkungen
        Produktmanager           Tim Klein              0123/XXXXXXX              tk@muster.de
        Anforderungsanalyst      Bianca Maaßen          0123/XXXXXXX              bm@muster.de
        Datenbankentwickler      Svenja Kirmes          xxxxxxxxxxx               xxxxxxxxxx
        Qualitätsmanagement      Kai Kristian Sefczyk   xxxxxxxxxxxx              xxxxxxxxxx
        Backend-Entwickler          
        Forntend-Entwickler      Süheyl Mustafa         xxxxxxxxxxxx              xxxxxxxxxx                


# 3 Konzept

    3.1 Ziel(e) der Anbieter
        Ziel ist es den Papieraufwand zu reduzieren und die Daten von Dienstplan sowie Medikamenten so aktuell wie möglich zu halten.
    3.2 Ziel(e) und Nutzen der Anwender
        Die Dokumentation von Medikamentenvergabe sowie Dienstabwesenheit soll so einfach wie möglich gestaltet werden. Im Backend werden die Daten aufgenommen und gespeichert, zudem soll genau gespeichert werden wer welche Daten übergibt, um einfacher nachweisen zu können welcher Mitarbeiter zuständig ist.
    3.3 Zielgruppe(n)
        Die Software soll durch ein klares Interface auch für Computerunerfahrene einfach zu bedienen sein.
        Dazu dienen sparsam eingesetzte, größere und auffälligere Buttons, die eindeutig auf die Funktion hindeuten, die sie auslösen.
    

# 4 Funktionale Anforderungen

    4.1 Anforderung 1
        Rollen und Login
        Die Software soll die Verwaltung von Daten in einfacher übersichtlicher Art darstellen. 
        Mitarbeiter melden sich an der Software an. Dies kann durch Login mit gängiger Multifaktor Authentifizierung oder durch einen NFC-Chip geschehen. Zudem soll eine höhere Rolle des Admins für Herr Becker eingerichtet werden um Änderungen im Dienstplan sowie Medikamentenplan durchzuführen.
    4.2 Anforderung 2 
        Dienstplan
        Der Dienstplan soll und einer klaren Übersicht angezeigt werden. Dazu sollen 2 Varianten angezeigt werden. 
        Eine für den Mitarbeiter in der sein Ablauf der Patienten angezeigt ist. Und eine Variante in der alle Mitarbeiter aufgelistet sind. Sie Anzeige soll die Aufenthaltszeit sowie den jeweiligen  Patienten anzeigen.
        Urlaub und Abwesenheit Einreichung soll ebenfalls über den Dienstplan möglich sein. Dazu ein separater Reiter, indem man seine verbliebenen Urlaubstage einsehen kann.
    4.3 Anforderung 3
        Medikamentendokumentation
        Medikamentendokumentation soll für jeden Patienten mit genauer Bezeichnung und Dosis angezeigt werden. Zudem muss aktiv die Einnahme Bzw. die Verabreichung der Medikamente bestätigt werden    von Mitarbeiter diese wird dann in die Datenbank aufgenommen. Sollte zum Ende der Zeit einer Patientenzeit ein Medikament der Liste nicht verabreicht worden sein wird der Mitarbeiter über ein
        Pop-Up informiert. Bei doppelter Eintragung wird der Mitarbeiter ebenfalls informiert.
        Medikamentenpläne können über einen Admin (z.B. Herr Becker) angepasst werden.
    4.4 Anforderung 4
        Offline-Modus
        Ein Offline-Modus dient dazu, um Daten Lokal zu speichern, sollte keine Internetverbindung bestehen. 
        Der Offline-Modus soll farblich klar angezeigt werden. 
        Bei nächstmöglicherInternetverbindung werden die Lokalen Daten auf den Server geladen und aktualisiert.

# 5 Nichtfunktionale Anforderungen

    5.1 Allgemeine Anforderungen
        Die Bedienung muss für nicht technisch geschultes Personal geeignet sein. Die Software muss eine intuitive und leicht verständliche Benutzeroberfläche bieten, um Barrierefreiheit zu gewährleisten.
        Schnelle Reaktionszeit der Benutzeroberflache.
    5.2 Gesetzliche Anforderungen
        Sollten sich während der Projektlaufzeit gesetzliche Anforderungen ändern, sind diese zu berücksichtigen. Die daraus resultierenden Anpassungen sind gesondert zu bewerten und ggf. als
        Erweiterung des Leistungsumfangs zu behandeln. Die Software muss alle geltenden Datenschutzbestimmungen erfüllen (insbesondere DSGVO). Personenbezogene und medizinische
        Daten sind entsprechend zu schützen. Zugriffe müssen nachvollziehbar protokolliert werden. 
        MFA zur Sicherung sensibler Daten.
    5.3 Technische Anforderungen
        Die Software muss auf NFC-fähigen Tablets lauffähig sein. Es muss ein Offline-Modus vorhanden sein.
        Daten müssen bei Wiederherstellung der Verbindung synchronisiert werden. Das System muss eine hohe Verfügbarkeit gewährleisten.


# 6 Lieferumfang
    6.1 Lieferumfang
        Software zur Dokumentation zur Unterstützung im Pflegealltag. Lieferumfang sind fünf Tablets sowie fünf NFC Chips mit bereits Installierter Software PflegeAssi. Die benötigten Endgeräte (Tablets mit NFC-Funktion) werden vom Auftraggeber bereitgestellt.
        Diese werden dem Auftragnehmer für Entwicklungs- und Testzwecke zur Verfügung gestellt, um eine optimale Anpassung der Software sicherzustellen.
    6.2 Kosten
        Für die Software sind 20.000€ eingeplant sowie ein jährliches Wartungsbudget von 10–20 % der Anschaffungskosten. Die Tablets mit Panzerglas und Hüllen werden separat von Herr Becker   angeschafft.
    6.3 Liefertermin
        Das Produkt soll über einen Zeitraum von drei Monten entwickelt werden. Beginn mit Abschluss des Vertrags.
        
    6.4 Ansprechstelle und Lieferort
        Ansprechstelle ist SoftStar mit telefonischer Ansprechstelle bei Herr Tim Klein oder Frau Bianca Maaßen.
        Lieferung und Schulung der Software erfolgt bei der Firma Becker Pflege & Betreuung nach Abschluss des Projektes.

# 7 Abnahmevoraussetzungen

    Die Abnahme der Software erfolgt, wenn folgende Voraussetzungen erfüllt sind:
    • Alle im Lastenheft definierten funktionalen Anforderungen wurden umgesetzt
    • Die Software ist auf den vorgesehenen Endgeräten (Tablets mit NFC-Funktion) lauffähig
    • Die Benutzer können sich erfolgreich per Login oder NFC anmelden
    • Die Funktionen zur Dienstplanung, Patientenverwaltung und Medikamentendokumentation sind vollständig nutzbar
    • Der Offline-Modus funktioniert und synchronisiert Daten nach Wiederherstellung der Verbindung
    • Die gesetzlichen Anforderungen (besonders Datenschutz) sind erfüllt
    • Eine Einweisung / Schulung der Mitarbeiter wurde durchgeführt
    • Es dürfen keine kritischen Fehler vorhanden sein

