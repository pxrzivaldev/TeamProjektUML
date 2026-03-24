Helfer sagt Anfrage zu

Akteur:
Helfer

Kurzbeschreibung:
Ein Helfer nimmt eines der vorgeschlagenen Hilfegesuche eines Suchenden an.

Vorbedingungen:

Der Helfer ist registriert und eingeloggt
- Das Hilfegesuch ist aktiv und noch nicht vollständig vergeben
- Das Hilfegesuch passt zu den Fähigkeiten des Helfers

Nachbedingungen:
- Das Hilfegesuch ist dem Helfer zugeordnet oder als „in Bearbeitung“ markiert
- Der Suchende wird über die Annahme benachrichtigt

Hauptablauf:
1. Der Helfer erhält eine Benachrichtigung über ein passendes Hilfegesuch (basierend auf Fähigkeiten und ggf. Ausrüstung)
2. Der Helfer öffnet das Hilfegesuch und prüft die Einsatzdaten (Beschreibung, Ort, Zeit, Anforderungen)
3. Der Helfer bewertet, ob er die Anforderungen erfüllen kann und verfügbar ist
4. Der Helfer wählt die Option „Anfrage zusagen“
5. Das System prüft, ob das Hilfegesuch weiterhin verfügbar ist
6. Das System ordnet das Hilfegesuch dem Helfer zu bzw. markiert es als „in Bearbeitung“
7. Das System sendet eine Benachrichtigung an den Suchenden über die Annahme

Alternativabläufe:
Hilfegesuch nicht mehr verfügbar
    In Schritt 5 stellt das System fest, dass das Gesuch bereits vergeben ist
    Der Helfer erhält eine entsprechende Meldung
    Der Use Case endet ohne Zuordnung

Helfer lehnt ab / bricht ab
    Der Helfer entscheidet sich gegen die Annahme und verlässt die Ansicht
    Es erfolgt keine Statusänderung



Suchender erstellt Anzeige

Akteur: Suchender /BOS

Beschreibung: 
- Eine Organisation erstellt ein Hilfsgesuch für einen Einsatz.

Vorbedingungen:
- Benutzer ist als BOS registriert und eingeloggt

Nachbedingungen:
- Hilfsgesuch ist gespeichert
- Passende Helfer werden identifiziert und benachrichtigt

Hauptablauf:
    
1. BOS öffnet Funktion „Anzeige erstellen“
2. Eingabe aller Einsatzdaten (Ort, Zeit, Tätigkeiten etc.)
3. Festlegung von Anforderungen (Fähigkeiten, Ausrüstung)
4. Angabe benötigter Helfer (Anzahl, etc.)
5. Bestätigung der Eingaben
6. System speichert Gesuch
7. System startet Matching-Prozess
8. Fragt bei Helfern an

Alternativablauf:
Ungültige Eingaben -> Fehlermeldung -> Korrektur