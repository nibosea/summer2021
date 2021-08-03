# MongoDBって何

[OpenStandia オープンソースまるごと](https://openstandia.jp/oss_info/mongodb/)を参考に書いてるよ． 

JSON形式のデータを蓄えるデータベース管理システム（DBMS)
ドキュメント指向データベースに分類されるらしい．

> JSON形式>
> JavaScript Object Notation…JavaScriptにおけるオブジェクトの表記をベースとした軽量なデータ記述言語．
>
> どきゅめんと指向データベース>
> 1件分のデータをドキュメントと呼び，JSONというデータ形式でデータを扱う．
> もはや，データを階層構造のドキュメントで扱う，データを階層構造のJSOＮで扱う．といっても過言ではない．
>
> データを表形式で保存するリレーショナルデータベースと**異なり**,スキーマ（テーブル定義）が必要ないことが大きな特徴．
> ドキュメントを複雑な階層でも管理することが出来るうえ，クエリやインデックスの作成が容易である．
> 大量データでもスケール（拡張）しやすい仕組みを持つ．scalabilityが高い．（大きさを変更できる）
> スキーマレスデータベース（スキーマがいらない），NoSQL(NotOnly SQL)データベース（リレーショナルデータベースだけではない）という呼び方もされている．

MongoDBはドキュメント指向データベースの中でもかなり利用されている方で，C++で書かれている．
商用製品にはMarkLogic．クラウドサービスではMicrosoft Azure CosmosDBがドキュメント型NoSQLとされているらしいよ．

![image-20210803152831028](C:\Users\cs19038\git\summer2021\mongoDB\picture\image-20210803152831028.png)

[https://openstandia.jp/oss_info/mongodb/]の写真を借りた．

特徴

- JSONはリッチなデータ構造であり，複雑なデータを扱いやすい

- 柔軟なクエリ． SQLライクなクエリで扱いやすい．

  例・コレクションpresonから3つ探す．db.person.find( {"name": "watanabe", "age" :30}).limit(3)

- RDBMSと同様に，多様なインデックスを作成可能

うん，この写経飽きた．実際に触ってみるか．

# 実際に触ってみよう

[やってみようNoSQL MongoDBを最速で理解する](https://qiita.com/Brutus/items/8a67a4db0fdc5a33d549)．
ええやん個の記事．そのまんまやん．

とりあえず今日はインストールして軽く触るだけで.16:00まで．

[stack-overflow](https://stackoverflow.com/questions/51417708/unable-to-install-mongodb-properly-on-ubuntu-18-04-lts)要はsudo apt installl mongoDB?
まぁなんか，多分良し．

うざ，動かん．しんどいわキレた．放置します．