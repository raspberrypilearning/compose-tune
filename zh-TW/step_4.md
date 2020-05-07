## 重複鈴聲

門鈴經常發出重複的提示音。

+ 讓我們把鈴聲放進一個循環裡：
    
    ![截圖](images/tune-times.png)
    
    Sonic Pi 將有助於把門鈴聲代碼縮進 `times`循環內。

+ 聽聽看鈴聲。 這是您所期望的鈴聲嗎？
    
    您需要在結尾前添加一行 `sleep` ，這樣才能在重複前暫停：
    
    ![截圖](images/tune-sleep2.png)

+ 再聽一次鈴聲，它聽起來應該更好聽了。
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/doorbell-2.mp3" type="audio/mpeg"> 您的瀏覽器不支援 <code>audio</code>。 </audio>
    </div>