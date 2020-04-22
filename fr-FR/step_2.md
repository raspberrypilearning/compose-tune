## Jouer tes premières notes

Sonic Pi te permet de programmer de la musique. Commençons par jouer de simples notes musicales.

[[[sonic-pi-install]]]

+ Lance Sonic Pi. Ton responsable de club pourra te dire où le trouver. Si tu utilises un Raspberry Pi alors c'est sous Programmation dans le menu.
    
    ![capture d'écran](images/tune-GUI.png)

+ Vois où ça dit «#Bienvenue dans Sonic Pi»? En dessous, tape:
    
    ![capture d'écran](images/tune-play.png)

+ Clique sur «Run». As-tu entendu une note musicale? Dans le cas contraire, assures-toi que le son n'est pas muet sur ton ordinateur et que le volume est suffisamment élevé. Si le son est trop fort, diminue-le.
    
    Si tu utilises un Raspberry Pi alors assure-toi d'utiliser un moniteur HDMI avec des haut-parleurs ou des haut-parleurs ou des écouteurs connectés à la prise audio.
    
    Il y a aussi un réglage de volume sous « Prefs » que tu peux ajuster.

+ Maintenant, ajoute une autre ligne en dessous de ta première ligne:
    
    ![capture d'écran](images/tune-play2.png)

+ Clique sur «Run». As-tu entendu ce que tu attendais? Dans Sonic Pi, `play` signifie commencer à jouer, donc il commence à jouer la première note et commence immédiatement à jouer la deuxième note de sorte que tu entends les deux notes en même temps.

+ Pour obtenir la deuxième note à jouer après la première note, ajoute une ligne `sleep 1` entre les deux pour que ton code ressemble à ceci:
    
    ![capture d'écran](images/tune-sleep.png)

+ Exécute maintenant ton code et il devrait ressembler à une sonnette de porte.
    
    Écoute et tu devrais entendre une note plus élevée puis une note inférieure. Les notes plus élevées ont des nombres plus élevés.
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/doorbell-1.mp3" type="audio/mpeg"> 
    Ton navigateur ne supporte pas l'élément <code>audio</code>. 
    </audio>
    </div>
+ Enregistre ton code en cliquant sur «Save» et nomme ton fichier «doorbell.txt».
    
    ![capture d'écran](images/tune-save.png)
    
    Si tu n'es pas sûr, vérifie auprès de ton responsable de club où tu devras enregistrer ton dossier.
    
    Tu peux recharger des fichiers dans Sonic Pi en cliquant sur «Load».