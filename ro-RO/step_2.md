## Redă primele note

Sonic Pi îți permite să programezi muzică. Să începem prin redarea unor note muzicale simple.

[[[sonic-pi-install]]]

+ Pornește Sonic Pi. Liderul clubului tău îți va spune unde să îl găsești. Dacă folosești un Raspberry Pi, atunci este în meniul Programare.
    
    ![captură de ecran](images/tune-GUI.png)

+ Vezi unde se afișează "#Welcome to Sonic Pi"? Scrie dedesubt:
    
    ![captură de ecran](images/tune-play.png)

+ Fă clic pe "Run". Ai auzit o notă muzicală? Dacă nu, asigură-te că sunetul nu este dezactivat pe computer și că volumul este suficient de ridicat. Dacă sunetul este prea puternic, dă-l mai încet.
    
    Dacă folosești un Raspberry Pi, asigură-te că ai fie un monitor HDMI cu difuzoare, fie difuzoare sau căști conectate la mufa audio.
    
    De asemenea, există în "Prefs" o setare a volumului pe care o poți ajusta.

+ Acum, adaugă o altă linie sub prima:
    
    ![captură de ecran](images/tune-play2.png)

+ Fă clic pe "Run". Ai auzit ceea ce așteptai? În Sonic Pi, `joaca` mijloc de a începe redarea, așa că începe să joace prima notă și apoi începe imediat redarea a doua notă , astfel încât să auziți ambele note în același timp.

+ Pentru a obține cea de-a doua notă pentru a reda după prima notă, adăugați o linie între `1` , astfel încât codul dvs. să arate astfel:
    
    ![captură de ecran](images/tune-sleep.png)

+ Acum rulați codul dvs. și ar trebui să sune ca un sunet de sunet.
    
    Ascultați și ar trebui să auziți o notă mai mare și apoi una mai mică. Notele mai mari au numere mai mari.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/doorbell-1.mp3" type="audio/mpeg"> Browserul dvs. nu acceptă elementul <code>audio</code>. </audio>
    </div>
+ Salvați codul dând clic pe "Salvați" și denumiți fișierul "doorbell.txt".
    
    ![captură de ecran](images/tune-save.png)
    
    Dacă nu sunteți sigur, contactați-vă pe Club Leader unde să salvați fișierul.
    
    Puteți încărca fișierele înapoi în Sonic Pi făcând clic pe "Încărcare".