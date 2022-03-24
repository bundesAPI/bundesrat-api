# Bundesrat API

Bundesrat: Live Informationen


## startlist_table.xml

**URL:** https://www.bundesrat.de/iOS/v3/startlist_table.xml?view=renderXml

Übersicht API Endpunkte



## aktuelles_table.xml

**URL:** https://www.bundesrat.de/iOS/v3/01_Aktuelles/aktuelles_table.xml?view=renderXml

Aktuelles



## termine_table.xml

**URL:** https://www.bundesrat.de/iOS/v3/02_Termine/termine_table.xml?view=renderXml

Termine



## plenum_kompakt_table.xml

**URL:** https://www.bundesrat.de/iOS/v3/03_Plenum/plenum_kompakt_table.xml?view=renderXml

Plenum Kompakt



## plenum_aktuelleSitzung_table.xml

**URL:** https://www.bundesrat.de/iOS/SharedDocs/3_Plenum/plenum_aktuelleSitzung_table.xml?view=renderXml

Plenum aktuelle Sitzung



## plenum_toChronologisch_table.xml

**URL:** https://www.bundesrat.de/iOS/SharedDocs/3_Plenum/plenum_toChronologisch_table.xml?view=renderXml

Plenum Chronologisch



## plenum_naechsteSitzungen.xml

**URL:** https://www.bundesrat.de/iOS/SharedDocs/3_Plenum/plenum_naechsteSitzungen.xml?view=renderXml

Plenum nächste Sitzung



## mitglieder_table.xml

**URL:** https://www.bundesrat.de/iOS/SharedDocs/2_Mitglieder/mitglieder_table.xml?view=renderXml

Mitglieder



## stimmverteilung.xml

**URL:** https://www.bundesrat.de/iOS/v3/06_Stimmen/stimmverteilung.xml?view=renderXml

Stimmverteilung



## bundesrat_praesidium.xml

**URL:** https://www.bundesrat.de/iOS/v3/05_Bundesrat/Praesidium/bundesrat_praesidium.xml?view=renderXml

Präsidium


## Beispiel

```bash
result=$(curl -m 60 https://www.bundesrat.de/iOS/v3/startlist_table.xml?view=renderXml)
```

