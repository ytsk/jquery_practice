# jQueryの使い方

## jQueryをダウンロードする

1. jQueryのサイトにアクセスする  
[ここ](http://jquery.com/download/)をクリックする．  
1. jQueryをダウンロードする  
サイト内にある `Download the compressed, production jQuery 3.0.0` を右クリックし，リンク先を保存するを選ぶ．  
(保存先はいったんデスクトップなどわかりやすい場所にしておく)  

## jQueryを使う

1. jQueryを使う準備をする  
ダウンロードした `jquery-3.0.0.min.js` というファイルを，jQueryを使いたいプロジェクトの中に移動させる．  
(ex. `MyWebSite/js` というフォルダの中に入れる)  
1. jQueryを使う  
jQueryを呼び出すコードを，HTML内の，<body>タグ内一番下に書き入れる．  

```html
<script src="./js/jquery-3.0.0.min.js"></script>
```

↑上記は先ほどのjQueryのファイルを， `js` というフォルダに入れたという前提．  
この一行を書き入れたHTMLファイルから見て，jQueryのファイルがどこにあるかを `src=" "` に書き入れてあげる．  

これでjQueryを使う準備は整いました．  

## jQueryライブラリを使う

[ここ](http://coliss.com/articles/build-websites/operation/javascript/best-jquery-plugins-and-scripts-2015.html)にまとめられているように，jQueryを利用したライブラリは非常にたくさんあります．  
基本的には，どれも使い始め方は同じです．  
まず，先ほど書いたようにjQueryを読み込むタグをHTMLに書いた後，jQueryを利用したライブラリのjsファイルを読み込むタグをHTMLに書きます．  

たとえば[これ](http://git.blivesta.com/animsition/)を使いたいとします．  
まずファイルをダウンロードし，その中のファイルをそれぞれ，自分が使いたいプロジェクトのフォルダに入れます．  
その後，HTMLに以下を記入します．

```html
<!-- animsition.css -->
<link rel="stylesheet" href="./css/animsition.min.css">
<!-- jQuery -->
<script src="./js/jquery-3.0.0.min.js"></script>
<!-- animsition.js -->
<script src="./js/animsition.min.js"></script>
```

ここでのポイントは，ダウンロードしたファイルを，jQueryのファイルよりも下に貼り付けるところです．  
ライブラリは，jQueryを利用したものであるため，先にjQueryを読み込まなければいけません．  

ここまでの使い方はどのライブラリもだいたい共通だと思われます．  
ここからの使い方は各ライブラリのドキュメントを参考にするか，随時質問をしてください．  
