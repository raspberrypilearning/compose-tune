## Wiederholen Sie den Klang

Türklingeln wiederholen oft das Glockenspiel.

+ Lassen Sie uns das Klingelzeichen in eine Schleife bringen:
    
    ![Screenshot](images/tune-times.png)
    
    Sonic Pi wird den Klingelcode innerhalb der `mal-` Schleife hilfreich einrücken.

+ Hören Sie das Glockenspiel. Ist es das, was du erwartet hast?
    
    Sie müssen am Ende eine `Schlaf` Zeile hinzufügen, damit eine Pause eintritt, bevor Sie das wiederholen:
    
    ![Screenshot](images/tune-sleep2.png)

+ Hören Sie das Glockenspiel erneut und es sollte besser klingen.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/doorbell-2.mp3" type="audio/mpeg"> Ihr Browser unterstützt das <code>Audio-</code> Element nicht. </audio>
    </div>