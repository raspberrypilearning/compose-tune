## 呼び鈴をくり返す

玄関（げんかん）の呼び鈴はしばしば音をくり返します。

+ ループの中に玄関（げんかん）の呼び鈴を入れましょう：
    
    ![スクリーンショット](images/tune-times.png)
    
    Sonic Pi will helpfully indent the doorbell chime code inside the `times` loop.

+ Listen to the chime. Is it what you expected?
    
    You'll need to add a `sleep` line at the end so that there's a pause before repeating:
    
    ![screenshot](images/tune-sleep2.png)

+ Listen to the chime again and it should sound better.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/doorbell-2.mp3" type="audio/mpeg"> Your browser does not support the <code>audio</code> element. </audio>
    </div>