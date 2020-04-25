## 最初の音符を演奏する

Sonic Piを使うと音楽をプログラムすることができます。 かんたんな音符を再生することからはじめてみましょう。

[[[sonic-pi-install]]]

+ Sonic Piを実行します。 クラブ・リーダーがどこにあるのかを教えてくれます。 Raspberry Piを使っているなら、メニューの「プログラミング」にあります。
    
    ![スクリーンショット](images/tune-GUI.png)

+ 「# Welcome to Sonic Pi」がどこに書かれているかわかりますか？ その下に次のように入力します。
    
    ![スクリーンショット](images/tune-play.png)

+ 「run」をクリックします。 音符が聞こえましたか？ 聞こえない場合は、コンピュータの音が消音されていないこと、音量が十分に大きいことを確認してください。 音が大きすぎる場合は音量を下げてください。
    
    Raspberry Piを使っているなら、スピーカー付きモニタをHDMIで接続して使用するか、スピーカーやヘッドフォンがオーディオジャックに接続されているか確認してください。
    
    There's also a volume setting under 'Prefs' that you can adjust.

+ Now add another line below your first one:
    
    ![screenshot](images/tune-play2.png)

+ Click 'Run'. Did you hear what you were expecting? In Sonic Pi, `play` means start playing, so it starts playing the first note and then immediately starts playing the second note so you hear both notes at the same time.

+ To get the second note to play after the first note add a `sleep 1` line in between so that your code looks like this:
    
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