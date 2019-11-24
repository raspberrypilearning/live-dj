## Einen Bass hinzufügen

Jetzt fügen wir dem Musikstück einige Bassnoten hinzu.

+ Erstelle zuerst einen neuen `live_loop` mit dem Namen `:bass`. Dieser neuer Loop sollte auch durch `sync` mit dem Schlagzeug synchronisiert werden.
    
    ![Screenshot](images/dj-bass-loop.png)

+ Erweitere das Programm so, dass alle 8 Takte eine einzelne Note gespielt wird. Die Note wird mit dem `:chipbass` Synthesizer gespielt.
    
    ![Screenshot](images/dj-bass-note.png)

+ Klicke das Wiedergabebutton (Du musst die Wiedergabe nicht erst beenden und erneut starten). Du solltest alle 8 Takte eine Note hören.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/bass-single.mp3" type="audio/mpeg"> Dein Browser unterstützt das <code>Audio-</code> Element nicht. </audio>
    </div>
+ Ein **Akkord** ist eine Gruppe von zusammen gespielten Noten.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/chord.mp3" type="audio/mpeg"> Dein Browser unterstützt das <code>Audio-</code> Element nicht. </audio>
    </div>
    Statt die gleiche Note alle 8 Takte zu spielen, kannst du eine zufällige Note aus einem **Akkord** wählen. In diesem Fall aus dem **C Moll** Akkord.
    
    ![Screenshot](images/dj-bass-random-note.png)

+ Das "mittlere" C ist eigentlich `:c4`. Um tiefere Basstöne zu spielen, füge nach dem Akkordnamen eine Zahl hinzu die kleiner als 4 ist.
    
    ![Screenshot](images/dj-bass-lower-note.png)

+ Mit dem Befehl `sustain` kannst du entscheiden für wie viele Takte die Note gehalten wird.
    
    ![Screenshot](images/dj-bass-longer-note.png)

+ Du kannst auch den `amp`-Befehl nutzen, um die Lautstärke des Basses zu wählen. Eine Zahl kleiner als 1 ist leiser und eine Zahl größer als 1 ist lauter. Denke daran die Dezimalzahlen mit Punkt statt Komma zu schreiben.
    
    ![Screenshot](images/dj-bass-amp.png)

+ Du kannst auch ein (lauteres) Sample hinzufügen, das am Anfang jeder Note gespielt wird.
    
    ![Screenshot](images/dj-bass-sample.png)

+ Klicke auf das Wiedergabebutton, um die Änderungen zu hören. Du musst die Wiedergabe dazu nicht erst beenden und erneut starten.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/bass.mp3" type="audio/mpeg"> Dein Browser unterstützt das <code>Audio-</code> Element nicht. </audio>
    </div>