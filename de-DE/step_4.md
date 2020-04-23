## Wiederhole die Tonfolge

Türklingeln wiederholen oft die gleiche Tonfolge.

+ Lass uns die Tonfolge in einer Schleife abspielen:
    
    ![Screenshot](images/tune-times.png)
    
    Sonic Pi rückt die Tonfolge innerhalb der `times` Schleife ein.

+ Höre dir die Tonfolge an. Ist es das, was du erwartet hast?
    
    Am Ende musst du ein `sleep` Kommando hinzufügen, damit eine Pause gesetzt wird, bevor sich die Schleife wiederholt:
    
    ![Screenshot](images/tune-sleep2.png)

+ Höre dir die Tonfolge erneut an. Sie sollte nun besser klingen.
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/doorbell-2.mp3" type="audio/mpeg"> 
    Ihr Browser unterstützt das <code>Audio-</code> Element nicht. 
    </audio>
    </div>