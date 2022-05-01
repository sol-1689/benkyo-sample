
# Webサイトを表示する仕組み_補足

## なにこれ？  
Webサイトを表示する仕組みについて、長くなったので分割しました。  





#### ブラウザがHTTPリクエストを送るタイミング

- aTagから遷移
aタグに設定されているURLを表示します。  



- formからのsubmit


- javascriptからのリクエスト  



#### Webサーバーへのパラメータの渡し方

- クエリストリング


- リクエストボデイ
  - formのsubmit時

  - プログラムでの実装時 


#### HTTPメソッド

- GET

- POST

API公開している例上げる

URLは同じですがにHTTPメソッドの違いにより動作が異なります。  
APIを利用する側にとっても分かりやすい為、このような作りになっている物も多いです。


#### SPA（シングルページアプリケーション）とは



#### Webアプリケーションの公開  


## Webアプリケーションの呼び方
Webサイトの集合体。
例えばECサイトならマイページ、商品一覧、注文ページなど、それらを表示する為の機能をまとめたものをWebアプリケーションという。

図
各ページの図＋プログラムをWebサイトに乗せる図？





・MDN HTTPについての説明サイト  
https://developer.mozilla.org/ja/docs/Web/HTTP


・MDN URLとは何か  
https://developer.mozilla.org/ja/docs/Learn/Common_questions/What_is_a_URL


・サーバー
https://wa3.i-3-i.info/word144.html


・tomcat
https://wa3.i-3-i.info/word12843.html
https://thinkit.co.jp/free/article/0708/2/1
https://agency-star.co.jp/column/tomcat


・アプリケーションサーバー

https://www.otsuka-shokai.co.jp/words/application-server.html

アプリケーションサーバーにはアプリケーションプログラムによって以下のような種類がある。
（1）Java：「Tomcat」「Glass Fish」
（2）PHP：「Apache」
（3）Ruby：「Unicorn」「Thin」「Rainbows」「Puma」

マイクロソフトのIIS（Internet Information Services）はWebサーバーとアプリケーションサーバーの機能を統合しVisual Basic、C#などの言語で記述したプログラムが作動している。

Appサーバーをwebサーバーとして利用しない理由
https://qiita.com/yCroma/items/e46476e2ac7c372bb2a3

2015年Webサーバアーキテクチャ序論
https://blog.yuuk.io/entry/2015-webserver-architecture



・ブラウザ周りの仕様
https://qiita.com/megmogmog1965/items/e180d02be711cecdc038
