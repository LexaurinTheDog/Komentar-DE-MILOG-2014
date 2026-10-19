# Quellenkarten und Rechercheprotokoll

## Gesetz

- Quelle: https://www.gesetze-im-internet.de/milog/xml.zip
- Abrufdatum: 19.10.2026; genauer UTC-Zeitpunkt und Antwort-Header in [verification.json](sources/verification.json).
- Konsolidierungsstand: Zuletzt geändert durch Art. 8 Abs. 3 G v. 12.5.2026 I Nr. 137.
- Original: [ZIP](sources/official.zip), [XML](sources/official.xml), [kanonische Extraktion](sources/canonical.md).
- SHA-256: XML `f9133387b010444d85b54e6473e3f5d57aab3553cc2125422aa2da49cbde51f3`.
- Bestehender Katalogtext: `/Volumes/LaCie/law-intake/eu/de/gesetze/gii-milog.md`; unverändert belassen.

## Tatsächliche Recherche

Am 19.10.2026 wurde mit Firecrawl die Abfrage `site.bundesarbeitsgericht.de Mindestlohn 5 AZR 135/16 9 AZR 162/18` ausgeführt. Die originale Antwort steht in [search.json](sources/search.json). Danach wurden die folgenden amtlichen BAG-Volltexte abgerufen und in HTML sowie Text gesichert. Trefferbeschreibungen allein wurden nicht zur Begründung verwendet. Die Suche ist thematisch begrenzt; nicht belegte Abwesenheit von Entscheidungen wird nicht behauptet. Für die übrigen Paragraphen wurde keine gesonderte umfassende Einzelnormsuche durchgeführt. Dort enthält diese Ausgabe keine eigenständige Rechtsprechungsautorität.

### BAG, 25.05.2016 – 5 AZR 135/16

- Amtlicher Volltext: https://www.bundesarbeitsgericht.de/entscheidung/5-azr-135-16/
- Zuordnung: § 1; Aussage: Erfüllung und Anrechnung tatsächlich geleisteter Zahlungen; insbesondere Rn. 22 ff..
- Beleg: [HTML](sources/5-azr-135-16.html), [Text](sources/5-azr-135-16.txt), [Abruf und SHA-256](sources/5-azr-135-16.json).
- Grenze: fallbezogene Aussage; kein Beleg für sämtliche Voraussetzungen heutiger oder abweichender Sachverhalte.

### BAG, 18.09.2018 – 9 AZR 162/18

- Amtlicher Volltext: https://www.bundesarbeitsgericht.de/entscheidung/9-azr-162-18/
- Zuordnung: § 3; Aussage: Transparenz einer nach dem 31.12.2014 vereinbarten Ausschlussklausel ohne Mindestlohnausnahme; Rn. 34 ff..
- Beleg: [HTML](sources/9-azr-162-18.html), [Text](sources/9-azr-162-18.txt), [Abruf und SHA-256](sources/9-azr-162-18.json).
- Grenze: fallbezogene Aussage; kein Beleg für sämtliche Voraussetzungen heutiger oder abweichender Sachverhalte.

## Ergänzende amtliche Normen

[§ 14 AEntG](https://www.gesetze-im-internet.de/aentg_2009/__14.html) wurde wegen der Haftungsverweisung in § 13 abgerufen; Sicherung und Hash: [aentg-14.json](sources/aentg-14.json), [HTML](sources/aentg-14.html).

Die zusätzliche Suchabfrage `site:gesetze-im-internet.de 2026 Mindestlohn 13,90 MiLoV5` ist in [search-rate.json](sources/search-rate.json) dokumentiert. Die [MiLoV5](https://www.gesetze-im-internet.de/milov5/BJNR10C0A0025.html) wurde anschließend amtlich vollständig abgerufen: [HTML](sources/milov5.html), [Abruf und Hash](sources/milov5.json). § 1 bestimmt 13,90 Euro ab 01.01.2026 und 14,60 Euro ab 01.01.2027; § 2 Inkrafttreten am 01.01.2026. Weitere Branchen- und Ausführungsverordnungen sind nicht Gegenstand einer vollständigen Verordnungsrecherche.

## Unabhängige Nachprüfung am 19.10.2026

Die ursprünglichen Abrufzeitpunkte bleiben unverändert. [Neue tatsächliche Abrufe einschließlich HTTP-Ergebnis, Zeit und Hash](sources/second-pass-verification.json) bestätigen die unveränderte amtliche XML-Fassung. [Katalogabgleich](sources/review-intake-comparison.json). Eine XML-Buildzeit wird nicht als alleiniger Beweis der Wirksamkeit jedes historischen Rechtsstands behandelt.

Die sauberen BAG-Textlesefassungen wurden aus dem unveränderten Original-HTML neu erzeugt; das HTML ist die maßgebliche archivierte Antwort. Die Nachprüfung hat die drei verwendeten Entscheidungen überprüft, keine vollständige neue Einzelnormrecherche ausgeführt.

BAG 5 AZR 135/16: Rn. 19 zur tatsächlich geleisteten Arbeit, Rn. 22–33 zur Anspruchskonkurrenz, Monatsbezug, endgültigen Verfügbarkeit und monatlichen Zwölfteln der Jahressonderzahlungen. Der dortige Betrag von 8,50 Euro und die damalige Bußgeldnummer sind historisch; heute ist Nichtzahlung § 21 Abs. 1 Nr. 13 zugeordnet. Keine Entscheidung zur Höhe 2026.

BAG 9 AZR 162/18: Tatsächlicher Streit um Urlaubsabgeltung; Rn. 34–46 zur Transparenz und zeitlichen Einordnung, Rn. 51 zur möglichen gesetzlichen Sammelausnahme, Rn. 56–60 zu den Folgen der unteilbaren Klausel. Keine ungeprüfte Übertragung auf ausgehandelte Individualklauseln.

Zusätzlich amtlich verifiziert: [MiLoDokV XML](https://www.gesetze-im-internet.de/milodokv_2015/xml.zip), [Abrufdatensatz](sources/review-milodokv.json), [gesicherte XML](sources/review-milodokv.xml). § 1 Abs. 1 und 2 enthält Entgelt- und Angehörigenausnahmen für die ausdrücklich genannten allgemeinen Melde-/Dokumentationspflichten; Absatz 3 verlangt weiterhin deutschsprachige Inlandsunterlagen zum Ausnahmennachweis. Die Rechercheabfrage `site:gesetze-im-internet.de MiLoDokV Mindestlohndokumentationspflichtenverordnung` ist in [review-search-milodokv.json](sources/review-search-milodokv.json) gesichert. Sonstige Ausführungsverordnungen wurden weiterhin nicht vollständig geprüft.

[Amtlicher Vorspann einschließlich allgemeiner Hinweise](sources/amtlicher-vorspann.txt); maschinell aus dem ersten XML-Normknoten gewonnen.
