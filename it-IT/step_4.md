## Ripeti lo squillo

I campanelli spesso ripetono lo squillo.

+ Mettiamo lo squillo del campanello in un ciclo:
    
    ![screenshot](images/tune-times.png)
    
    Sonic Pi indenterà utilmente il codice della campanella all'interno del ciclo `times` (volte).

+ Ascolta lo squillo. È quello che ti aspettavi?
    
    Devi aggiungere una linea `sleep` di attesa alla fine in modo che ci sia una pausa prima di ripetere:
    
    ![screenshot](images/tune-sleep2.png)

+ Ascolta di nuovo lo squillo e dovrebbe suonare meglio.
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/doorbell-2.mp3" type="audio/mpeg"> 
    Il tuo browser non supporta l'elemento <code>audio</code>. 
    </audio>
    </div>