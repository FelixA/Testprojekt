# <a name="Benutzerhandbuch"></a> Benutzerhandbuch

## <a name="SucheinderVEA"></a> Suche in der VEA

### <a name="AllgemeineHinweise"></a> Allgemeine Hinweise

#### <a name="MandantPrüfen"></a> Mandant Prüfen

Platzhalter mandant-prüfen.png

Bevor Sie eine Suche starten, prüfen Sie bitte den eingestellten Mandanten (siehe Abbildung 1). 

Platzhalter mandant-wechseln.png

Sollten Sie sich im falschen Mandanten befinden, so können Sie diesen durch einen Klick auf die eigene Kennung (siehe Abbildung 2) einstellen.

### <a name="TippsundTricks"></a> Tipps und Tricks
#### <a name="SchnelleexakteSuche"></a> Schnelle exakte Suche

Statt das Häckchen auf "Exakt" zu setzen, kann der Suchtext auch in Gänsefüßchen "" gepackt werden.

#### <a name="ÜberprüfungBesuchterDateien"></a> Überprüfung besuchter Dateien

Sobald eine Datei angeklickt wurde, verfärbt sich der Hyperlink von Blau in Rot.
Dies bleibt für mehrere Sessions bestehen, d.h. auch wenn der Internet Explorer geschlossen und neu geöffnet wird, bleibt der Link als besucht markiert. Möchten Sie die Speicherung der besuchten Links zurücksetzen, so können Sie das über den Internet Explorer mit Mausklick auf "Sicherheit" --> "Browserverlauf löschen". 

Vorsicht: Dieser Befehl löscht den gesamten Verlauf des Browsers!

#### <a name="direkteSucheNachKENr"></a> Direkte Suche Nach KE Nr

Plathalter suche-ke-direkt.png

Es ist möglich direkt nach einer KE Nr. zu suchen. Dazu kann diese einfach in das Feld KE Identifikation eingetragen werden, welches in Abbildung XX dargestellt wird.

### <a name="Suchbegriffe"></a> Suchbegriffe

Das Suchfenster "Suchbegriffe" stellt die zentrale Suche nach bestimmten Kriterien. Diese können exakt, oder vage ("fuzzy") formuliert werden. 
Sucht man beispielsweise nach Holz, so erhält man eine Liste an Ergebnissen, die an irgendeiner Stelle den Begriff Holz enthalten. 

Platzhalter suche-holz.png

Dabei ist der Begriff immer nur nach rechts vage, d.h. Begriffe Holzbau oder Holzmast werden der Ergebnisliste hinzugefügt, ein Begriff wie Unterholz wird nicht in die Ergebnisliste aufgenommen. 

####<a name="Besonderheiten"></a> Besonderheiten

### <a name="Identifikation"></a> Identifikation

Das Feld Identifikation benötigt eine eindeutige Identifikation des Dokuments als Input-Parameter, d.h. die KE-Nr.
Auch hier ist der Begriff nach rechts vage.

### <a name="Bereich"></a> Bereich

Der Bereich des betreffenden Dokuments.

### <a name="Hauptgruppe"></a> Hauptgruppe

Die Hauptgruppe des betreffenden Dokuments.

### <a name="Untergruppe"></a> Untergruppe

Die Untergruppe des betreffenden Dokuments.

### <a name="Dokumententyp"></a> Dokumententyp

Der Dokumententyp des betreffenden Dokuments.

### <a name="Anzahl"></a> Anzahl

Die Anzahl der maximal zu findenden Dokumente. Hier gilt, der Wert sollte so gering wie möglich sein. Desto mehr Dokumente geladen werden müssen, desto langsamer funktioniert die Suche, bzw. die Anzeige der Ergebnisse. 

## <a name="DefinierteMetadatenSuche"></a> Definierte Metadaten Suche

Sobald 
- Bereich 
- Hauptgruppe 
- Untergruppe 
- Dokumententyp 

ausgewählt wurden, kann eine Suche anhand von Metadaten durchgeführt werden. Diese variiert von Dokumententyp zu Dokumententyp, da diese spezifische Metadaten besitzen.

Platzhalter suche-metadaten.png

Wie in Abbildung X zu sehen ist, wurden 17 Einträge aus dem:
- Bereich Umspannwerke
- Hauptgruppe Handakte
- Untergruppe Übergreifend
- Dokumenttyp Ü - Handakte - Übergreifend 

mit den Metadatensätzen:
- UW-Kürzel GROGH
- und Langtext Schriftverkehr gefunden

## <a name="UndefinierteMetadatenSuche"></a> Unspezifische Metadaten Suche
Wird der Dokumenttyp nicht ausgewählt, so lässt sich eine Metadaten Suche über alle Dokumenttypen durchführen.
Hierbei lassen sich bis zu drei Attribute auswählen, nach denen exakt, oder vage gesucht werden können.
