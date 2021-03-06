マーベリック開発部門トレーニング用のレポジトリです。社内の機密事項は含まないので、公開しています。

マーベリック開発部門のメンバーはこちらから[「課題提出トレーニングのポリシー」](https://docs.google.com/document/d/18SWcDVK_urhA4FOpwyjax2d6ZhDA-k9L4mFQnQrMhec/edit#)も確認して下さい。

「[実践Scala入門](https://www.amazon.co.jp/%E5%AE%9F%E8%B7%B5Scala%E5%85%A5%E9%96%80-%E7%80%AC%E8%89%AF-%E5%92%8C%E5%BC%98-ebook/dp/B07JP9STPW/ref=sr_1_2?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&keywords=scala&qid=1581858808&s=digital-text&sr=1-2)」を中心に、書籍などから課題を出します。 この課題をこなすことがのScalaトレーニングのゴールです。
GitHubにPull Requestとして提出する課題を用意し、課題の提出によって達成感を味わってもらうようにします。

提出する際にはこのレポジトリを個人のレポジトリとしてForkして下さい。
課題一つ一つの提出をPull Requestとして挙げて下さい。Pull RequestのApprovalをもって課題完了の確認とします。

## この課題で身につく能力

「〇〇の内容をマスターする」だと際限なく課題の量が膨れ上がるので、課題は必要な量だけにします。書籍なら2〜3割内容を把握できる分量が目安です。ソフトウェア開発技術の勉強は一生つづくので、技術者はこの課題だけでなく、結局様々な分野を様々な方法で勉強をするからです。

- PlayGround, REPL, IDEで素早くScalaソースコードを書き実行できる
- 数値型や文字型などの基本型を使った結合などの基本操作ができる
- 戻り値と引数の型を正しく組み合わせて簡単なクラスを書ける
- (クラス図を渡されれば)traitおよびclassをextendsして簡単なクラスを作れる
- companion objectとcase classを使える
- if/else、パターンマッチを使える
- Option、Either、Exceptionを使ってエラー表現できる
- Seq、Set、Mapなど基本的なコレクションとそれらの主な違い、メソッドを把握して使える
- Futureを使った非同期処理を含むソースコードが読め、スレッドの動きを図に起こして説明できる
- forをmapとflatMapに手書き展開できる
- ミュータブル・イミュータブルの使い方の違いとイミュータブルの必要性を理解している
- 型システム、AnyとかAnyValとかNothingについて大まかに把握している

## 参考書籍・オンラインテキスト:

書籍はマーベリック社の本棚にあります。自分で買う必要はありません。

こちらのテキストを中心に勉強していきます。
- [実践Scala入門](https://www.amazon.co.jp/%E5%AE%9F%E8%B7%B5Scala%E5%85%A5%E9%96%80-%E7%80%AC%E8%89%AF-%E5%92%8C%E5%BC%98-ebook/dp/B07JP9STPW/ref=sr_1_2?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&keywords=scala&qid=1581858808&s=digital-text&sr=1-2)

また副読教材として以下の2つを挙げます。いわゆるコップ本、Scalaスケーラブルプログラミング入門は世界中で(英語版があります)Scalaの入門テキストとして使われています。しかし難しい内容も多く扱われていて、プログラミング経験の少ない読者にはわからない部分が多いでしょう。一方、プログラミング言語経験者とくにJava経験者であれば、コップ本の内容はおおまかに理解できるでしょうが、それでも高度な内容がたくさんあります。Scala四年目の私リチャードが読んで未だにわからない内容もあります。
- [Scalaスケーラブルプログラミング第3版](https://www.amazon.co.jp/Scala%E3%82%B9%E3%82%B1%E3%83%BC%E3%83%A9%E3%83%96%E3%83%AB%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B0%E7%AC%AC3%E7%89%88-Martin-Odersky-ebook/dp/B01LYPRFI7/ref=sr_1_3?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&keywords=scala&qid=1581858808&s=digital-text&sr=1-3)
- [Scala研修テキスト (オンライン)](https://scala-text.github.io/scala_text/)

<img width=200 src="https://user-images.githubusercontent.com/7414320/76287981-06d8e080-62e9-11ea-8ae1-f8538c43e5c9.png"><img width=200 src="https://user-images.githubusercontent.com/7414320/76287992-0c362b00-62e9-11ea-8f91-0cbf0cf124d5.png"></td>
