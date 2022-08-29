# Lern-Bericht
Oliver Much

## Einleitung

In diesem Lernbericht über das Modul 133 beschreibe ich das benutzen von Image-Tags in JSF.

## Was habe ich gelernt?

Ich habe gelernt, wie man in JSF ein Bild in eine Webseite einbauen kann. 

## Beschreibung

In *html*, sowie in *JSF* können Bilder eingebunden werden. In *html* werden Bilder mit einem `<img>`-Tag, in *JSF* hingegen mit einem `<h:graphicImage>` eingebunden. 


In der `img` library unter dem `resources`-Ordner befindet sich das Bild `kh.jpg` mit einer festgelegten Breite von 200px. 
```
<h:graphicImage library="img" name="kh.jpg" width="200"></h:graphicImage>
```

Auf der Webseite:

![image](https://user-images.githubusercontent.com/69577485/187264672-f8f83150-aafd-460b-ada4-8c8685289777.png)


Der `resources` und `img`-Ordner müssen wie folgt erstellt und das Bild dort abgelegt werden. 

![Netbeans](https://user-images.githubusercontent.com/69577485/187268175-cbb5091b-d6bf-4b1b-a9e3-12d0bc19139f.gif)

## Verifikation

In den Medien ist zu erkennen, dass man in *JSF* Bilder anderst und komplizierter verlinkt als in *html*. Um ein Bild mittels *JSF* auf einer Webseite darstellen zu können, sind mehrere Schritte nötig. 

# Reflektion zum Arbeitsprozess

👍 Das Dokumentieren und Beschreiben meiner Arbeitschritte ist mir gut gelungen. Auch den Code für die Verlinkung des Bildes zu schreiben, viel mir leicht. In diesem Modul fühle ich mich bis jetzt relativ sicher. 

👎 Ich habe viel Zeit beim Verliken meines Bildes verloren, da ich meinen eigenen Fehler nicht fand. Nach langer und sehr genauer Überprüfung habe ich festegestellt, dass ich den `resources`-Ordner ein Verzeichnis zu tief (im `WEB-INF`-Ordner) erstellt hatte. 

**VBV**: Ich sollte mich nächsten Mal besser auf die *leichten* Aufgaben konzentrieren (Hier spezifisch das Erstellen der Ordner). 
