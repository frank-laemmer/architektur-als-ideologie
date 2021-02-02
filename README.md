# Zur digitale Ausgabe von Architektur als Ideologie

Der Text "Architektur als Ideologie" ist ein Aufsatz von Heide Berndt aus dem Jahr 1968. Dieses Repository widmet sich der Digitalisierung des Textes.

## Downloads

+ [architektur-als-ideologie.epub](architektur-als-ideologie.epub)
+ [architektur-als-ideologie.pdf](architektur-als-ideologie.pdf)

## Struktur und Inhalt

+ Beabreitbare Textdateien im Markdown Dateiformat in Ordner`src`
+ Exporte des Textes in verschiedenen Endformaten: 
  + ebook `.epub`
  + PDF `.pdf`
+ Scans der Schreibmaschinenseiten als Quelldateien 

## Status

Mit OCR Technologie wurde die Bilddateien in Text umgewandelt. Die Interpretation ist natürlich nicht fehlerfrei. Viele Fehler wurden schon beseitigt, einige sind noch drin.

## Mitmachen

Pull Requests werden gerne entgegengenommen.

## Generierung der Exporte

Die Endformate können aus den Markdown-Dateien erstellt werden. Pandoc ist ein Dateiformatierungsprogramm. Hier sind sind die Befehle zum erstellen der Endformate:


```shell
  # Create epub ebook
  pandoc src/metadata.txt src/text.md -o architektur-als-ideologie.epub --css=src/epub.css

  # Create PDF ebook
  pandoc src/metadata.txt src/text.md -o architektur-als-ideologie.pdf
```

Mehr Informationen zur technischen Umsetzung finden sich auf [diesem Medium Blog Post](https://frank-laemmer.medium.com/from-analog-text-to-e-book-e1a90dcbe92).

## Lizenz

Der Text kann unter share alike Bedingungen genutzt werden. Mehr hier: [LICENSE.md](LICENSE.md)

Die Original Scans wurden mit freundlicher Genehmigung des Het Nieuwe Instituut - [hetnieuweinstituut.nl](https://hetnieuweinstituut.nl/) - zur Verfügung gestellt. Die Grafiken stehen unter Copyright:  Collection Het Nieuwe Instituut/ BROZ, 506.6-16


## Kontakt

heide@franklaemmer.de