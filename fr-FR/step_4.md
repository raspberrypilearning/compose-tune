## Répéter la sonnerie

Les sonnettes de porte répètent souvent la sonnerie.

+ Mettons la sonnette de la porte dans une boucle :
    
    ![capture d'écran](images/tune-times.png)
    
    Sonic Pi indentera utilement le code de la sonnerie de porte à l'intérieur de la boucle `times`.

+ Écoute la sonnerie. C'est ce que tu attendais ?
    
    Tu devras ajouter une ligne `sleep` à la fin pour qu'il y ait une pause avant de répéter :
    
    ![capture d'écran](images/tune-sleep2.png)

+ Écoute à nouveau la sonnerie et elle devrait paraître mieux.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/doorbell-2.mp3" type="audio/mpeg"> Ton navigateur ne supporte pas l'élément <code>audio</code>. </audio>
    </div>