# Buchhändlerportraits (Deutsches Buch- und Schriftmuseum der Deutschen Nationalbibliothek)

## Beschreibung

> Mehr als 2.400 Bildnisse von Buchhändlern, Buchdruckern und Verlegern des 17. bis 20. Jahrhunderts

## Anzeige im Katalog

- [portal.dnb.de](https://portal.dnb.de/opac.htm?query=cod%3Dd029+location%3Donlinefree+&method=simpleSearch&cqlMode=true)

## Datensets mit Hyperlinks zu Bilddateien

- [Download](https://data.dnb.de/Buchhaendler/) (MARC21-xml)
- OAI: [set=dnb:digitalisate-oa:projekt29](https://services.dnb.de/oai2/repository?verb=ListRecords&metadataPrefix=mets&set=dnb:digitalisate-oa:projekt29) (METS/MODS-xml)

## Lizenz

> Alle Titeldaten der Deutschen Nationalbibliothek und die Normdaten der Gemeinsamen Normdatei (GND) sind kostenfrei unter „Creative Commons Zero“-Bedingungen (CC0 1.0) zur freien Nutzung verfügbar.

## Quelle

- [dnb.de/dnblab](https://www.dnb.de/dnblab)

# Bereitstellung der Metadaten zu den Buchhändlerportraits

## Software

- [Wget](https://www.gnu.org/software/wget/)
- [Catmandu](https://librecat.org/Catmandu/)
    - [Catmandu::OAI](https://metacpan.org/release/Catmandu-OAI)

## Routine

- [`./retrieve`](./retrieve)

## XML-Dateien

- [`marc21/records.xml`](./marc21/records.xml)
- [`mets-mods/records.xml`](./mets-mods/records.xml)
