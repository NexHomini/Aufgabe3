# __LaTeX-Unterlagen__

"In diesem Repository beinden sich die LaTeX-Unterlagen zum Modul."

## __Inhalt__

Der Inhalt entspricht dem Text der Aufgabe 2 des Modul.

Es kann sinnvoll sein, sich die PDF zur Aufgabe zwei noch einmal
anzusehen

## __PDF Erstellen__

Das geht ganz schnell und einfach:

- Zuerst installieren wir LaTeX (tug.org/texlive/)
- Dann nutzen wir PDFLaTeX zum Erstellen des PDF
	"pdflatex ./task.tex" (Das muessen wir mehrfach machen, damit die PDF auch fertig wird)
- Alternativ koennen wir auch einfach LaTeX Mk nutzen 
	"latexmk -pdf ./task.tex"

**!!ACHTUNG!!**

LaTeX erstelle einige nervige Dateien (.aux, .log) diese muss man loeschen bevor
man einen Commit mit seinen Aenderungen macht!
