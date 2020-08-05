## Añade una muestra

Agreguemos una muestra en bucle sobre la secuencia de la batería.

+ Para tocar una muestra sincronizada con tu batería, crea otro `live_loop` llamado `:sample`.
    
    ![captura de pantalla](images/dj-sample-loop.png)

+ Añade la muestra `:loop_compus`, haciendo que se reproduzca cada 8 tiempos.
    
    ![captura de pantalla](images/dj-sample-bug.png)

+ Si pruebas tu muestra, ¡notarás que **no coincide en absoluto con la batería**!
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/beat-bug.mp3" type="audio/mpeg"> Tu navegador no es compatible con el elemento <code>audio</code>. 
    </audio>
    </div>
+ Lo primero que deberás hacer es sincronizar tu muestra con el ritmo de la batería usando `sync`.
    
    ![captura de pantalla](images/dj-sample-sync.png)

+ ¡Esto todavía no suena bien! Añade código para imprimir la duración de la muestra:
    
    ![captura de pantalla](images/dj-sample-duration.png)

+ Si revisas el **log**, verás que aunque la muestra se repite cada 8 tiempos, **la muestra no dura 8 tiempos**.
    
    ![captura de pantalla](images/dj-sample-log.png)
    
    (Ahora puedes eliminar el código para imprimir la duración de la muestra.)

+ Para sincronizar tu muestra con la batería, tienes que **estirar** la muestra para que también dure exactamente 8 beats.
    
    ![captura de pantalla](images/dj-sample-stretch.png)

+ Prueba tu código presionando 'Ejecutar' nuevamente -- **¡No tienes que detener la música y reiniciarla**! Ahora al escuchar tu muestra te darás cuenta que está sincronizada con el ritmo de la batería.
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/beat-fixed.mp3" type="audio/mpeg"> Tu navegador no es compatible con el elemento <code>audio</code>. 
    </audio>
    </div>