## Bas toevoegen

Laten we nu wat basnoten toevoegen aan je muziek.

+ Begin met het maken van een nieuwe `live_loop` genaamd `:bass`. Deze nieuwe lus moet ook `sync` (synchroon lopen) met de drums.
    
    ![screenshot](images/dj-bass-loop.png)

+ Voeg code toe om elke acht tellen een enkele noot te spelen. De gespeelde noot gebruikt de `:chipbass` synth.
    
    ![screenshot](images/dj-bass-note.png)

+ Druk op 'Run' (je hoeft niet te stoppen en je muziek opnieuw te starten). Je zou elke 8 tellen een noot moeten horen spelen.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/bass-single.mp3" type="audio/mpeg"> Je browser ondersteunt het element <code>audio</code> niet. </audio>
    </div>
+ Een **chord** (akkoord) is een groep noten die samen worden gespeeld.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/chord.mp3" type="audio/mpeg"> Je browser ondersteunt het element <code>audio</code> niet. </audio>
    </div>
    In plaats van het spelen van dezelfde noot om de 8 tellen, kun je ook `kiezen` voor een willekeurige noot van een **akkoord**. In dit geval is het akkoord **C Mineur**.
    
    ![screenshot](images/dj-bass-random-note.png)

+ 'Middelste' C is eigenlijk `:c4`. Om lagere basnoten te spelen, voeg je een getal lager dan 4 toe na de akkoordnaam.
    
    ![screenshot](images/dj-bass-lower-note.png)

+ Gebruik een `sustain` om te kiezen voor hoeveel tellen de noot wordt aangehouden.
    
    ![screenshot](images/dj-bass-longer-note.png)

+ Je kunt ook `amp` gebruiken om het volume van de bas te kiezen. Een getal lager dan 1 wordt zachter en hoger dan 1 wordt luider.
    
    ![screenshot](images/dj-bass-amp.png)

+ Je kunt ook een (luidere) sample toevoegen om aan het begin van elke noot te spelen.
    
    ![screenshot](images/dj-bass-sample.png)

+ Druk op 'Run' om je code te testen. Het is niet nodig om je muziek te stoppen en opnieuw te starten.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/bass.mp3" type="audio/mpeg"> Je browser ondersteunt het element <code>audio</code> niet. </audio>
    </div>