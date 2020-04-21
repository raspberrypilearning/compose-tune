## Reprodueix les primeres notes

Sonic Pi et permet programar música. Comencem per reproduir algunes notes musicals senzilles.

[[[sonic-pi-install]]]

+ Executa Sonic Pi. El líder del teu club et podrà dir on trobar-lo. Si fas servir una Raspberry Pi, el trobaràs a l'apartat Programació del menú.
    
    ![captura de pantalla](images/tune-GUI.png)

+ Veus on diu #Benvingut a Sonic Pi'? A sota, escriu:
    
    ![captura de pantalla](images/tune-play.png)

+ Fes clic a 'Run'. Has escoltat una nota musical? Si no, assegura't que el so no està silenciat a l’ordinador i que el volum és prou alt. Si el so és massa fort, baixa'l.
    
    Si utilitzes una Raspberry Pi, assegura't que utilitzes un monitor HDMI amb altaveus o tingues altaveus o auriculars connectats a la presa d'àudio.
    
    També pots ajustar la configuració del volum a 'Prefs'.

+ Afegeix una altra línia per sota de la primera:
    
    ![captura de pantalla](images/tune-play2.png)

+ Fes clic a 'Run'. Did you hear what you were expecting? A Sonic Pi, `play` significa inicia reproducció, de tal manera que comença a reproduir la primera nota i immediatament després comença a tocar la segona nota, fent que les escoltis totes dues alhora.

+ Per escoltar la segona nota després de la primera, afegeix la línia `sleep 1` entre elles, de manera que el codi quedi així:
    
    ![screenshot](images/tune-sleep.png)

+ Now run your code and it should sound like a doorbell chime.
    
    Listen and you should hear a higher note and then a lower one. Higher notes have higher numbers.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/doorbell-1.mp3" type="audio/mpeg"> Your browser does not support the <code>audio</code> element. </audio>
    </div>
+ Save your code by clicking on 'Save' and name your file 'doorbell.txt'.
    
    ![screenshot](images/tune-save.png)
    
    If you're not sure, check with your Club Leader where you should save your file.
    
    You can load files back into Sonic Pi by clicking on 'Load'.