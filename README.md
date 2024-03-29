# DHGE - Praktische Informatik - Matrikel 21 - Semester 4

Dieses Repository ist ursprünglich aus dem Matrikel 19 geklont und wieder zum laufen gebracht worden.

Es entstand aus dem Studiengang "Praktische Informatik" der Dualen Hochschule Gera-Eisenach. Hier habe ich Mitschriften gesammelt und erweitert. Die Skripte liegen im `markdown`-Format vor. Zur besseren Handhabung (und weil Github nur begrenzte `markdown`-Features bereitstellt) werden diese zusätzlich automatisch in PDFs umgewandelt und zur Verfügung gestellt.

## Module

- [ABWL - Allgemeine Betriebswirtschaftslehre](./ABWL-LEDER)
- [DBS - Datenbanken](./DBS-DORENDORF)
- [ASM - Rechnerarchitekturen/hardwarenahe Programmierung](./ASM-GUENTHER)
- [SWE - Systemanalyse](./SWE-KASCHE)
- [PRO - IT-Trends](./PRO-KASCHE)
- [EMB - WPM 1 Embedded Systems](./EMB-GUENTHER)
- [OOP - WPM 1 Objektorientierte Programmierung / Java](./OOP-CASSELT)
- [SWS - WPM 1 Kryptographie und Softwaresicherheit](./SWS-KUSCHE)

Templatesammlung von SWE ist in einem [extra Repo](https://github.com/importPI20fromDHGE/dhge-pi20-sem4-swe)

## Markdown-Erweiterungen

Alle Skripte in diesem Repository sind im `markdown`-Format verfasst. Für dieses existieren [viele verschiedene Standards](https://de.wikipedia.org/wiki/Markdown#Weiterentwicklungen,_Variationen_und_Erg%C3%A4nzungen).
Auf Github selbst ist der Funktionsumfang von `markdown` im Vergleich zu anderen Standards deutlich eingeschränkt.
Es ist beispielsweise nicht möglich die Größe von Bilder zu definieren, Metadaten für Dokumente anzugeben oder Mathematische Formel darzustellen.
Aus diesem Grund wird [`pandoc`](https://pandoc.org/) verwendet, um `markdown`-Dateien mit vielen Funktionserweiterungen in PDFs umzuwandeln.
Damit eine Kompatibilität zum Github-`markdown` haben wir eigene Erweiterungen definiert, die im Folgenden beschrieben werden:

### Bildgröße

```md
![Bildbeschreibung](assets/a.png)<!--width=200px-->
![Bildbeschreibung](assets/b.png)<!--height=200px-->
```

### Pagebreaks usw

```md
<!--pagebreak-->
<!--newpage-->
<!--clearpage-->
```

### Mathematische Formel

Github unterstützt keine mathematischen Formeln.
Als Workaround gibt es eine [Erweiterung für Chrome](https://github.com/orsharir/github-mathjax).
Ansonsten können Formeln in ihrer vollen Pracht nur in den PDFs betrachtet werden.
