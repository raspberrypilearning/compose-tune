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

+ Fes clic a 'Run'. Has sentit el què esperaves? A Sonic Pi, `play` significa inicia reproducció, de tal manera que comença a reproduir la primera nota i immediatament després comença a tocar la segona nota, fent que les escoltis totes dues alhora.

+ Per escoltar la segona nota després de la primera, afegeix la línia `sleep 1` entre elles, de manera que el codi quedi així:
    
    ![captura de pantalla](images/tune-sleep.png)

+ Ara, executa el teu codi i hauria de sonar com un timbre de porta.
    
    Escolta, hauries de sentir una nota més alta i una altra de més baixa. Les notes altes tenen números més grans.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/doorbell-1.mp3" type="audio/mpeg"> El teu navegador no admet l'element <code>d'àudio</code>. </audio>
    </div>
+ Desa el codi fent clic a "Save" i posa-li "timbredeporta.txt" al fitxer.
    
    ![captura de pantalla](images/tune-save.png)
    
    Si no estàs segur, consulta amb el Líder del teu Club on s'hauria de desar.
    
    Pots carregar fitxers a Sonic Pi fent clic a 'Load'.