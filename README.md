# Übung01 - HelloAgain Aufgabenbeschreibung

### Projektbeschreibung: 
Dieses Projekt dient der Einarbeitung in Untiy für die selbstständige Erstellung zukünftiger 2D Projekte. 
Ein einfaches Unity 2D Projekt wird erstellt, als WebGL exportiert und auf GitHub Pages veröffentlicht. 
Das Projekt enthält eine Szene. Die Szene besteht aus einem screenindependent Canvas (960x600).
Auf dem Canvas befindet sich mindestens ein Text und ein Image GameObject. 
Die Benennung der Objekte in der Hierarchy, wie auch die Benennung der Elemente in der Project Pane, folgt der PascalCase Notation.

### Entwicklungsplattform: 
(Betriebsystem, Unity Version, Visual Studio Version, verwendete SDKs)

### Zielplattform: 
WebGL Referenzauflösung (960x600) 

### Visuelle Einblicke in das Projekt: 
Screenshots (Konzept, Spielabschnitte), Video (< 100MB, < 3 min)
![sc-ue01helloagain](https://user-images.githubusercontent.com/28704310/132992326-6bd52f52-8af3-48e5-8406-060d0270f158.JPG)

### Notwendiges für die Ausführung: 
z.B.: Installationsprozess, Schritt für Schritt Anweisung, spezielles Packages welches geladen werden muss, etc.  

### Drittmaterial: 
Falls verwendet Fonts, Sounds, Music, Graphics, Materials, Code etc. welches nicht von mir stammt muss hier referenziert werden. 

### Anforderungen:  
- [ ] Anlegen eines 2D Unityprojekts mit Namen HelloAgain-yourKürzel
- [ ] In Assets einen Folder MyGame erstellen und den Scenes Folder in diesen MyGame Folder ziehen
- [ ] Im Ordner Scenes die SampleScene in HelloAgain umbenennen
- [ ] Im Game View Einstellung 960x600 einstellen
- [ ] Der Szene ein Canvas GameObject hinzufügen
- [ ] Das Canvas screenindependent einstellen: 
- [ ] Canvas Componente Render Mode auf Screen Space – Camera einstellen und in Render Camera die Main Camera reinziehen.
- [ ] Canvas Scaler UI Scale Mode, Scale With Screen Size einstellen und als Reference Resolution 960 x 600 einstellen.
- [ ] Dem Canvas GameObject ein Text GameObject hinzufügen: „Hello again, here is yourKürzel speaking :) 
- [ ] Dieses Text GameObject umbenennen in Welcome
- [ ] Dem Canvas GameObject ein Image GameObject hinzufügen (Abmessung/Auflösung > 960x600)
- [ ] Dieses Image GameObject umbennen in Background
- [ ] Anordnung in der Hierarchy so ändern, dass der Background hinter dem Text liegt
- [ ] Im Ornder Assets > MyGame  einen Ordner Sprites anlegen, alle im Projekt verwendeten Sprites, die wir hinzufügen, dort ablegen.
- [ ] In das Image GameObject mit Namen Background ein Sprite in die Image Source ziehen 
- [ ] Assets und ProjectSettings Folders auf GitHub laden
- [ ] Readme updaten
- [ ] WebGL exportieren in HelloAgain-yourKürzel > docs
- [ ] Upload auf GitHub
- [ ] WebGL Pages Einstellen
- [ ] Link in Readme einfügen

### Optionale Aufgabenstellung:
- [ ] Grafische Aufbereitung des Projekts
- [ ] Zusätzliche Text und Sprite Elemente einfügen und platzieren
- [ ] Text visuell ändern: color, font, font style, etc.
- [ ] Textmesh pro GameObject einfügen und manipulieren 
- [ ] Color Tint Playmode einstellen

### Lessons Learned:
| Neu gelernt | Wiederholung | Vertiefung | Lernstoff                                                                             |
|-------------|--------------|------------|---------------------------------------------------------------------------------------|
|             |              |            | Anlegen eines 2D Unityprojektes                                                       |
|             |              |            | Screenindependent Design für 2D Einstellung des Canvas                                |
|             |              |            | GameView Auflösung Einstellung                                                        |
|             |              |            | Verwendung und Manipulation von UI Elementen Text, Image                              |
|             |              |            | Anordnung GameObjects in Hierarchy hat Auswirkung auf Anordnung der Elemente im Spiel |
|             |              |            | Unity Editor Komponenten: Game View, Scene View, Hierarchy, Inspector, Project        |
|             |              |            | (optional) Color Tint Playmode                                                        |
|             |              |            | WebGL exportieren                                                                     |
|             |              |            | WebGL auf GitHub Pages veröffentlichen                                                |


Copyright by you :)
