# Dokumentation Aufgabe 2
## Frank Hasenbalg, 571087
### Kopf-Modell
Das Modell des Kopfes ist von Makehuman. Ich habe ein menschliches Mesh generiert und als OBJ zusammen mit der Textur exportiert. Die beiden Teile habe ich in eine Blender-Szene geladen und alles entfernt, was nicht von Nutzen war.

![](doku/Capture.PNG)

### Shapekeys
Fuer die Shapekeys habe ich die Mundregion und den Unterkiefer des Kopfes verformt.
Aehnlichen lauten wurden die gleichen Formen zugewiesen.

![](doku/Capture5.PNG)

Meist habe ich *Proportional Editing* genutzt.

![](doku/Capture1.PNG)

![](doku/Capture2.PNG)

![](doku/Capture3.PNG)

![](doku/Capture4.PNG)

### Ball texturieren

Ich habe eine Kappe der Sphere in Quads verwandelt, den unteren Teil der Sphere geloescht unf mit dem Mirror-Modifier neu generiert.

![](doku/Capture8.png)

![](doku/Capture9.png)

Dann habe ich den Modifier angewendet und an einer Seite eine Naht gesetzt.

Abgewickelt wurde die Sphere mit der Option *Apply to Oppject* in *Sphere Projection*.

![](doku/Capture000010.png)

![](doku/Capture000011.png)

Dann habe ich eine neue Textur erstellt, auf die die Matereialien gebacken werden sollen .

![](doku/Capture000005.png)

Es wurden 2 Materialien angelegt. Ein rotes und ein weisses.

![](doku/Capture000006.png)

![](doku/Capture000007.png)

In beide Materialien babe ich im Cycles Node Editor einen Image Texture Node gelegt, dessen Bildpfad auf die Textur zeigt.

![](doku/Capture000008.png)

Zum backen nehm ich Mehl, Eier, Milch, Hefe und Ambient Occlusion und stelle dann im *Bake*-Menu aud Diffuse und *Color*.

![](doku/Capture000009.png)

Jetzt wird gebacken.

![](doku/Newfolder/Capture000010.png)

![](doku/Newfolder/Capture000011.png)

Meine gebackene Textur erinnert mich stark an die Oesterreichische Flagge.

![](doku/Newfolder/Capture000012.png)

Mit *F3* wird das Bild gespeichert und dann ueber das *External Data*-Menu un die Blender-Datei gepackt.

Fuer die neue Textur habe ich ein neues material angelegt, und als *Image Texture* die frischgebackene Flagge genommen.

![](doku/Newfolder/Capture000013.png)

![](doku/Newfolder/BallTex.png)

Die Textur in rot und weiss.

### Lipsync Animation

Ich habe "Der Ball" von Rilke mit dem Handy eingelesen.

![](doku/Capture6.PNG)

Die Datei habe ich in Blender geladen und dann Keyframes fuer die Shapekeys gesetzt.

![](doku/Capture7.PNG)

### Rendern

Ich habe die Rendereinstellungen wie folgt eingestellt:

![](doku/Newfolder/Capture000014.png)

Unter *Light Paths* habe ich zwei Haekchen weggenommen:
![](doku/Newfolder/Capture000015.png)
