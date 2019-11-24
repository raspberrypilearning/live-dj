## Ein Sample hinzufügen

Jetzt legen wir eines neues, sich wiederholendes Sample über unseren Drum-Loop.

+ Um ein Sample zeitgleich mit deinem Drum-Loop abzuspielen, programmieren wir einen weiteren `live_loop` mit dem Namen `:sample`.
    
    ![Screenshot](images/dj-sample-loop.png)

+ Füge das Sample `:loop_compus` ein, das jeden 8 Takt abgespielt werden soll.
    
    ![Screenshot](images/dj-sample-bug.png)

+ Wenn du dein Sample abspielst, merkst du, dass es **nicht zu dem Drum-Loop** passt!
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/beat-bug.mp3" type="audio/mpeg"> Dein Browser unterstützt das <code>Audio-</code> Element nicht. </audio>
    </div>
+ Erst musst du das Sample dem Schlagzeug anpassen. Verwende dazu den `sync` Befehl.
    
    ![Screenshot](images/dj-sample-sync.png)

+ Das hört sich aber immer noch nicht richtig an! Verwende den gezeigten Befehl, um die Länge des Samples auszugeben:
    
    ![Screenshot](images/dj-sample-duration.png)

+ Wenn du jetzt im **Protokoll** suchst, wirst du sehen, dass sich das Sample zwar alle 8 Takte wiederholt, **aber nicht ganz 8 Takte** dauert.
    
    ![Screenshot](images/dj-sample-log.png)
    
    (Du kannst jetzt den Befehl, dass die Länge des Samples anzeigt, wieder entfernen.)

+ Um das Sample dem Schlagzeug anzupassen, musst du es ein wenig **verlängern**, damit es auch genau 8 Takte dauert.
    
    ![Screenshot](images/dj-sample-stretch.png)

+ Klicke auf das Wiedergabebutton um deiner Änderungen zu hören- **Du musst die Wiedergabe dazu nicht erst beenden und erneut starten**! Du solltest jetzt hören, dass dein Sample zeitgleich mit deinem Drum-Loop gespielt wird.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/beat-fixed.mp3" type="audio/mpeg"> Dein Browser unterstützt das <code>Audio-</code> Element nicht. </audio>
    </div>