## Spielen Sie Ihre ersten Noten

Mit Sonic Pi können Sie Musik programmieren. Beginnen wir mit ein paar einfachen Noten.

[[[sonic-pi-install]]]

+ Führen Sie Sonic Pi aus. Ihr Clubleiter kann Ihnen sagen, wo Sie ihn finden können. Wenn Sie einen Raspberry Pi verwenden, finden Sie im Menü Programmierung.
    
    ![Screenshot](images/tune-GUI.png)

+ Sehen Sie, wo es heißt: "Willkommen bei Sonic Pi" Unten dort Typ:
    
    ![screenshot](images/tune-play.png)

+ Klicken Sie auf "Ausführen". Hast du eine Musiknote gehört? Wenn nicht, stellen Sie sicher, dass der Ton auf Ihrem Computer nicht stummgeschaltet ist und die Lautstärke hoch genug ist. Wenn der Ton zu laut ist, drehen Sie ihn herunter.
    
    Wenn Sie einen Raspberry Pi verwenden, stellen Sie sicher, dass Sie entweder einen HDMI-Monitor mit Lautsprechern verwenden oder Lautsprecher oder Kopfhörer an die Audiobuchse angeschlossen haben.
    
    Unter 'Prefs' können Sie auch die Lautstärke einstellen.

+ Fügen Sie nun eine weitere Zeile unter der ersten hinzu:
    
    ![screenshot](images/tune-play2.png)

+ Klicken Sie auf "Ausführen". Hast du gehört, was du erwartet hast? Bei Sonic Pi bedeutet `play` , dass die Wiedergabe beginnt, die erste Note beginnt und sofort die zweite Note gespielt wird, so dass Sie beide Noten gleichzeitig hören können.

+ Um die zweite Note nach der ersten Note abzuspielen, fügen Sie eine `zwischen 1 und` Zeile dazwischen ein, so dass Ihr Code folgendermaßen aussieht:
    
    ![Screenshot](images/tune-sleep.png)

+ Führen Sie nun Ihren Code aus und es sollte sich wie ein Klingelzeichen anhören.
    
    Hören Sie zu und Sie sollten eine höhere und dann eine tiefere Note hören. Höhere Noten haben höhere Zahlen.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/doorbell-1.mp3" type="audio/mpeg"> Ihr Browser unterstützt das <code>Audio-</code> Element nicht. </audio>
    </div>
+ Speichern Sie Ihren Code, indem Sie auf 'Speichern' klicken und Ihre Datei 'doorbell.txt' nennen.
    
    ![Screenshot](images/tune-save.png)
    
    Wenn Sie nicht sicher sind, wenden Sie sich an Ihren Clubleiter, wo Sie Ihre Datei speichern sollten.
    
    Sie können Dateien wieder in Sonic Pi laden, indem Sie auf "Laden" klicken.