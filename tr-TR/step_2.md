## İlk notlarınızı çalın

Sonic Pi müzik programlamanızı sağlar. Birkaç basit nota çalarak başlayalım.

[[[sonic-pi-install]]]

+ Sonic Pi'yi çalıştırın. Kulüp Lideriniz size bunu nerede bulabileceğinizi söyleyebilecektir. Eğer Raspberry Pi kullanıyorsanız, menüden Programlama seçeneğinin altında bulabilirsiniz.
    
    ![ekran görüntüsü](images/tune-GUI.png)

+ '#Sonic Pi'ye Hoşgeldiniz'? yazısını gördünüz mü? Bunun altına şunu yazın:
    
    ![ekran görüntüsü](images/tune-play.png)

+ "Çalıştır"a tıklayın. Bir müzik notası duydunuz mu? Duymadıysanız, öncelikle bilgisayar sesinin kapalı olup olmadığını, ya da sesin kısık olup olmadığını kontrol edin. Eğer ses çok yüksekse, sesi kısın.
    
    Raspberry Pi kullanıyorsanız, hoparlörlü bir HDMI monitör kullandığınızdan veya hoparlörünüzün ya da kulaklığınızın bilgisayarınıza bağlı olduğundan emin olun.
    
    Ayrıca 'Tercihler' seçeneğinden ses seviyesini ayarlayabilirsiniz.

+ Şimdi ilk satırınızın altına başka bir satır ekleyin:
    
    ![ekran görüntüsü](images/tune-play2.png)

+ "Run"a tıklayın. Sesi duydunuz mu? Sonic Pi'de `play` oynatmayı başlat anlamına gelir, yani önce ilk notayı hemen sonra da ikinci notayı çalmaya başlar, böylece her iki notayı da aynı anda duyarsınız.

+ İkinci notayı birinciden sonra çalmak için, iki nota arasına `sleep 1` komutunu eklerseniz kodunuz şöyle görünecektir:
    
    ![ekran görüntüsü](images/tune-sleep.png)

+ Şimdi, kodunuzu tekrar çalıştırdığınızda bir kapı ziline benzeyecektir.
    
    Sesi dinlediğinizde önce yüksek bir ses, sonra daha düşük bir ses duyacaksınız. Yüksek notaların sayıları da daha yüksektir.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/doorbell-1.mp3" type="audio/mpeg"> Your browser does not support the <code>audio</code> element. </audio>
    </div>
+ Kodunuzu 'Kaydet'i tıklayarak kaydedin ve dosyanızı' doorbell.txt' olarak adlandırın.
    
    ![ekran görüntüsü](images/tune-save.png)
    
    Eğer dosyanızı nereye kaydetmeniz gerektiğinden emin değilseniz, Kulüp Liderinize sorabilirsiniz.
    
    Dosyaları tekrar Sonic Pi'ya yüklemek için 'Yükle'ye tıklayın.