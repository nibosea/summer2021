# summer2021
 にぼしは，大学3年生の夏，何をしようか

1. インターンのための勉強 ＭONGO DB （データベース)

   [企業より，springBootお勉強はこれ使って](https://spring.pleiades.io/spring-boot/docs/current/reference/html/getting-started.html#getting-started.whats-next)

2. CTF

3. 研究室の夏開けに行われるセキュリティのテスト

4. VimGolf

5. AtCoder

6. なんか開発

8. 実験Ⅱの予習？FSに上がってゐると噂

8. マウスを左手で持つ練習と同時にキーボードを使いまくる練習\

9. インターンで作ったLineChatBotを、ポートフォリオに乗せるための加工を施す

まあなんか，思いついたら 書いていこう(季語:まぁなんか)





## SpringBootの学び方
[企業からもらった勉強用URL](https://spring.pleiades.io/spring-boot/docs/current/reference/html/getting-started.html#getting-started.whats-next)

これはなんか日本語多すぎてｳｳｪｴｴｴ；；；ってなっちゃう.とりあえず目は通して、動くことは確認したけど、仕様だとかｳｹﾞｳｹﾞｳｹﾞのｳｹﾞです。

[そこで、お手軽コース](https://spring.pleiades.io/guides)から、適当に好きな奴をやっていくと良いかもしれない！！   
とりあえずそれでやってみる。

やり方は、適当にやるタイトルのものを選ぶ。
で、やっていく過程で、Zipをダウンロードすることになるから、一行目の importのところだけちょっとイジイジするように気を付ければ勝てる！

[RestTemplateでRESTAPIの利用](https://spring.pleiades.io/guides/gs/consuming-rest/)を例に、具体的に実行してみる。

1. [Spring initializr](https://start.spring.io/)へアクセスする。
   1. ProjectはMaven、言語はJava,SpringBootのversion はspring --versionで出てきたやつ。
   2. Project Metadataは、なんかそれっぽく作る。場合によっては、最初のURL（RestTemplateがどうたら）の説明で指定されているかも。
   3. Ｄependencies → ＡDＤ→ Spring Webを選ぶ。
   4. Generateで生成して、保存。
2. unzipで生成したProjectを解凍する。
3. cdコマンドで、解答したふぉるだの中に入る。
4. src/main/とかで、hogeApplication.javaがある場所に、テキスト通りにファイルを作る。
5. ./mvnw spring-boot:run もしくは mvn spring-boot:runで実行。

終わり。

### ぶっちゃけ

コードをコピペして実行するだけだから、これ以上環境構築で苦しむことはなさそうだ！！スゴイ。

だからまあ、そろそろコードの意味とか考えながら実行してみよう。一個一個は15分でクリアできるものらしいからね。
