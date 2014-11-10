MathWIM
===========

The display and edit the formula in the HTML5 canvas feature.

HTML5 のキャンバス機能で数式を表示・編集

デモ
-----

[https://mathwim.github.io/demo.html](https://mathwim.github.io/demo.html)


使い方
------

1. [https://mathwim.github.io/mathwim.zip](https://mathwim.github.io/mathwim.zip) からファイルをダウンロード

2. zipファイルを解凍し、jsファイルをサイトフォルダに配置

3. head 部分に script タグを追加
	
	```
	 <script type="text/javascript" src="js/mathwim.min.js"></script>
	```
	
4. 数式を配置したい箇所にタグを追加
	```
	<object class="MathWIM"></object>
	```

ドキュメント
------------
[https://github.com/mathwim/MathWIM/wiki/Document](https://github.com/mathwim/MathWIM/wiki/Document)


開発環境構築
------------

1. node.js をインストール

2. ソースコードをクローンして、依存ライブラリのインストール

	```
	git clone https://mathwim.github.com/MathWIM 
	cd MathWIM 
	npm install
	```

3. grunt コマンドの実行

	```
	grunt
	 ```

4. src/ 以下のcoffee ファイルを変更すると public/js/mathwim.js, public/js/mathwim.min.js が更新されます。

TODO
----

 * MathML 入出力
 * LaTeX 入出力

LICENSE
-------

Undecided

Copyright (c) 2014 MEDIA PLUS INC.

Home Page
---------

[https://mathwim.github.io](https://mathwim.github.io)

[http://media-plus.co.jp/](http://media-plus.co.jp/)

