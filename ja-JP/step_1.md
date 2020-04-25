## はじめに

このプロジェクトでは、短い音色をプログラムします。 その音色は玄関（げんかん）の呼び鈴や携帯電話の着信音、コンピュータの警告通知に使ったり、ウェブページに入れたりすることができます。

<div id="audio-preview" class="pdf-hidden">
  玄関（げんかん）の呼び鈴がどのように鳴るのかを聞くには、下にある再生ボタンを押してください： <audio controls preload> <source src="resources/doorbell.mp3" type="audio/mpeg"> お使いのブラウザは<code>audio</code>要素をサポートしていません。 </audio>
</div>

### クラブ・リーダーのための追加情報

このプロジェクトを印刷する必要がある場合は、 [印刷用バージョン](https://projects.raspberrypi.org/en/projects/compose-tune/print)を使用してください。

## \--- collapse \---

## title：クラブ・リーダー用の覚書

## Introduction:

このプロジェクトでは、子どもたちは玄関（げんかん）の呼び鈴をプログラムして、番号を使って音符を演奏し、くり返しコードを使って音符をくり返す方法を学びます。

## 資料

このプロジェクトの「プロジェクト資料」は次の資料が含まれています：

##### クラブ・リーダー向け資料

「プロジェクト資料」のリンクをクリックすると、このプロジェクトの完成版が見つかります。完成版のプロジェクトには次のものが含まれています：

* doorbell.txt
* doorbell.mp3

## 学習目標

* MIDI番号を使った音符の演奏
* くり返し

このプロジェクトは [Raspberry Piデジタル・メイキング・カリキュラム](http://rpf.io/curriculum)の中から、以下の内容を取り扱います：

* [基本的なプログラミング構文を使って、簡単なプログラムを作る](https://www.raspberrypi.org/curriculum/programming/creator)

## チャレンジ

* 「呼び鈴をより良くする」 - 玄関（げんかん）の呼び鈴をより良くするために別の音符やタイミングを使ってみる。
* 「4回くり返す」 - 玄関（げんかん）の呼び鈴を4回くり返して、すごく迷惑になるようにする。
* 「新しい音色をつくる」 - 携帯電話の着信音など新しい音色をプログラムするのに学んだ技術を生かします。

## よくある質問

* 使う番号はMIDI番号で、21から108はピアノの音符に対応しています。
* On the Raspberry Pi you can use `aplay` from the command line to play `.wav` files.

\--- /collapse \---

## \--- collapse \---

## title: Project materials

## Club leader resources

* [Downloadable completed Sonic Pi project](resources/doorbell.txt)
* [Downloadable completed project mp3 file](resources/doorbell.mp3)

\--- /collapse \---