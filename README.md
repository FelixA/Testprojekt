# <a name="Benutzerhandbuch"></a> Benutzerhandbuch

## <a name="SucheinderVEA"></a> Suche in der VEA

### <a name="AllgemeineHinweise"></a> Allgemeine Hinweise

#### <a name="MandantPrüfen"></a> Mandant Prüfen

Platzhalter mandant-prüfen.png

Bevor Sie eine Suche starten, prüfen Sie bitte den eingestellten Mandanten (siehe Abbildung 1). 

Platzhalter mandant-wechseln.png

Sollten Sie sich im falschen Mandanten befinden, so können Sie diesen durch einen Klick auf die eigene Kennung (siehe Abbildung 2) einstellen.

### <a name="Suchverfahren"></a> Suchverfahren
#### <a name="SchnelleexakteSuche"></a> Schnelle exakte Suche

Plathalter schnelleexakteSuche.png

Diese schnelle Suche ist von der eigentlichen Suchmaske gelöst und befindet sich in der rechten oberen Ecke der Anwendung. Sie können direkt durch die Eingabe der Ihnen bekannten KE Nummer auf das Dokument gelangen.
Es wird keine Eingabetaste oder das Betätigen eines Suche-Buttons benötigt. 

#### <a name="direkteSucheNachKENr"></a> Direkte Suche Nach KE Nr

Plathalter suche-ke-direkt.png

Es ist möglich direkt nach einer KE Nr. zu suchen. Dazu kann diese einfach in das Feld KE Identifikation eingetragen werden, welches in Abbildung XX dargestellt wird. 

#### <a name="FreieSucheSchlagworte"></a> Freie Suche mittels Schlagworte

Plathalter freieSucheSchlagworte.png

Sie befinden sich in folgendem Szenario: Sie wissen spezielle Schlagwörter, welche in dem gesuchten Dokument vorkommen. Leider wissen Sie jedoch die KE-Nummer, also die eindeutige Identifikationsnummer, nicht. Im Falle eines solchen Szenarios können Sie innerhalb der Eingabezeile „Suchbegriffe“ das jeweilige Schlagwort eingeben. 

#### <a name="SucheAngabevonDokumententyp"></a> Suche durch Angabe von Dokumententyp-Informationen

Platzhalter sucheAngabevonDokumententyp.png

Sie wollen ein spezielles Dokument suchen, wovon Sie jedoch nur Dokumententyp-Informationen besitzen. Auf der Eingabemaske können Sie die Suchabfrage durch die Angabe von Dokumententyp-Information (Hauptgruppe, Untergruppe, Dokumententyp) weiter einschränken.

#### <a name="DefinierteMetadatenSuche"></a> Definierte Metadaten Suche

Platzhalter definierteMetadatenSuche.png

Wenn Sie die Dokumententyp-Informationen eingeben, so werden auf der rechten Seite der Suchmaske die Metainformationen angepasst. Diese Metadaten beziehen sich nur auf die Dokumente, bei denen die Dokumententyp-Informationen mit der  in der Suchmaske übereinstimmen.

#### <a name="FreieMetadatenSuche"></a> Freie Metadaten Suche

Platzhalter freieMetadatenSuche.png

Dieses Szenario bzw. Suchverfahren ist ähnlich wie das vorangegangene Beispiel „Definierte Metadaten Suche“. Hier sind Ihnen weder die KE-Nummer noch die Dokumententyp-Informationen bekannt. Sie wissen nur, dass das gesuchte Dokument bestimmte Metadaten beinhaltet.

### <a name="TippsundTricks"></a> Tipps und Tricks
#### <a name="ÜberprüfungBesuchterDateien"></a> Überprüfung besuchter Dateien
Sobald eine Datei angeklickt wurde, verfärbt sich der Hyperlink von Blau in Rot.Dies bleibt für mehrere Sessions bestehen, d.h. auch wenn der Internet Explorer geschlossen und neu geöffnet wird, bleibt der Link als besucht markiert. Möchten Sie die Speicherung der besuchten Links zurücksetzen, so können Sie das über den Internet Explorer mit Mausklick auf "Sicherheit" --> "Browserverlauf löschen". 
Vorsicht: Dieser Befehl löscht den gesamten Verlauf des Browsers!

#### <a name="ExaktsuchennachdemBegriff"></a> Exakt suchen nach dem Begriff
Statt das Häckchen auf "Exakt" zu setzen, kann der Suchtext auch in Gänsefüßchen "" gepackt werden.

### <a name="Suchbegriffe"></a> Suchbegriffe

Das Suchfenster "Suchbegriffe" stellt die zentrale Suche nach bestimmten Kriterien. Diese können exakt, oder vage ("fuzzy") formuliert werden. 
Sucht man beispielsweise nach Holz, so erhält man eine Liste an Ergebnissen, die an irgendeiner Stelle den Begriff Holz enthalten. 

Platzhalter suche-holz.png

Dabei ist der Begriff immer nur nach rechts vage, d.h. Begriffe Holzbau oder Holzmast werden der Ergebnisliste hinzugefügt, ein Begriff wie Unterholz wird nicht in die Ergebnisliste aufgenommen. 

### <a name="Identifikation"></a> Identifikation
Das Feld Identifikation benötigt eine eindeutige Identifikation des Dokuments als Input-Parameter, d.h. die KE-Nr.
Auch hier ist der Begriff nach rechts vage.

### <a name="Bereich"></a> Bereich
Der Bereich stellt eine technische Abgrenzung des Mandanten.

### <a name="Hauptgruppe"></a> Hauptgruppe
Die Hauptgruppe stellt die erste Ebene innerhalb der technischen Abgrenzung (Bereich) da.

### <a name="Untergruppe"></a> Untergruppe
Die Untergruppe ist wiederrum eine Unterteilungen der Hauptgruppe.

### <a name="Dokumententyp"></a> Dokumententyp
Der Dokumententyp des betreffenden Dokuments.

### <a name="Anzahl"></a> Anzahl
Die Anzahl der maximal zu findenden Dokumente. Hier gilt, der Wert sollte so gering wie möglich sein. Desto mehr Dokumente geladen werden müssen, desto langsamer funktioniert die Suche, bzw. die Anzeige der Ergebnisse. 

