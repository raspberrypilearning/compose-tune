## 呼び鈴をくり返す

玄関（げんかん）の呼び鈴はしばしば音をくり返します。

+ ループの中に玄関（げんかん）の呼び鈴を入れましょう：
    
    ![スクリーンショット](images/tune-times.png)
    
    Sonic Piは`times`ループの中に入る玄関（げんかん）の呼び鈴のコードをインデントしてくれます。

+ 呼び鈴を聞いてください。 期待した通りでしたか？
    
    くり返す前に休止するように最後に`sleep`を追加する必要があります。
    
    ![スクリーンショット](images/tune-sleep2.png)

+ 呼び鈴をもう一度聞くと、音がより良くなっているはずです。
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/doorbell-2.mp3" type="audio/mpeg"> 
      お使いのブラウザは<code>audio</code>要素をサポートしていません。 
    </audio>
    </div>