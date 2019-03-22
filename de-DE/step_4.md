## Probe hinzufügen

Fügen Sie ein Loop-Sample über der einfachen Drum-Loop hinzu.

+ Um ein Sample zeitlich mit Ihrem Schlagzeug abzuspielen, erstellen Sie eine weitere `live_loop` Namen `: Sample`.
    
    ![Screenshot](images/dj-sample-loop.png)

+ Fügen Sie das Sample `: loop_compus`, damit es alle 8 Beats abgespielt wird.
    
    ![screenshot](images/dj-sample-bug.png)

+ Wenn Sie Ihr Sample testen, werden Sie feststellen, dass **nicht zu den Drums** passt.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/beat-bug.mp3" type="audio/mpeg"> Ihr Browser unterstützt das <code>Audio-</code> Element nicht. </audio>
    </div>
+ Das erste , was Sie tun müssen, ist `sync` Ihre Probe mit dem Trommelschlag.
    
    ![screenshot](images/dj-sample-sync.png)

+ Das hört sich immer noch nicht richtig an! Fügen Sie Code hinzu, um die Dauer des Beispiels zu drucken:
    
    ![screenshot](images/dj-sample-duration.png)

+ Wenn Sie durch **log**zurückblättern, werden Sie feststellen, dass das Sample zwar alle 8 Schläge wiederholt, **aber nicht ganz 8 Schläge**dauert.
    
    ![Screenshot](images/dj-sample-log.png)
    
    (Sie können jetzt den Code entfernen, um die Beispieldauer zu drucken.)

+ Um entsprechen Ihre Probe mit den Trommeln Sie benötigen , um **Strecke** die Probe , so dass es genau 8 Schläge als auch dauert.
    
    ![Screenshot](images/dj-sample-stretch.png)

+ Testen Sie Ihren Code, indem Sie erneut auf "Ausführen" klicken - **Sie müssen die Musik nicht stoppen und erneut starten**! Sie sollten jetzt hören, dass Ihr Sample zeitlich mit Ihrem Drum-Beat gespielt wird.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/beat-fixed.mp3" type="audio/mpeg"> Ihr Browser unterstützt das <code>Audio-</code> Element nicht. </audio>
    </div>