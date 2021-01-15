---
title: "オンライン投稿のやり方"
---
投稿方法
=====
MojaCoderの[問題を投稿](https://mojacoder.vercel.app/problems/post)へアクセスします。

![投稿画面](https://storage.googleapis.com/zenn-user-upload/zbdne95dmcztc5bdk26jfaqb6t73)
☝️のような画面が表示されると思います。
各々の項目を設定した後、投稿ボタンを押すと投稿できます。

問題文タブ
-----
![問題文タブ](https://storage.googleapis.com/zenn-user-upload/1gd4dtfxxqxhwkinrdwqcs4yrjcb)

### 問題Slug
これは問題ページのURLに使われる文字列です。
例えば問題Slugがa-plus-bのとき、問題ページへのURLは`mojacoder.vercel.app/users/ユーザー名/problems/a-plus-b`となります。
設定できる文字列に現在特に制限を設けていませんが、URLを見やすくするためにアルファベットでなるべく短い文字数で構成した方が良いでしょう。

:::message
同じユーザーで同じ問題Slugの問題を複数投稿することはできません。
新しい問題で古いものが上書きされます。
:::

### タイトル
問題のタイトルです。
問題一覧に表示されるので魅力的なものを設定しましょう。

### 問題文
問題本体です。Markdown記法に対応しています。
数式はTex記法で表現してください。
また、制約やサンプルなどの情報もここに含めてください。

#### 具体例
例として[A + B](https://mojacoder.vercel.app/users/Makutamoto/problems/a-plus-b)の原文を示します。
絶対にこれに従う必要があるわけではないのでプレビューなどを活かして各々で色々試してみましょう。
````Markdown
問題文
=====
$A + B$を出力して下さい。

制約
-----
- $0 \leq A \leq 100$
- $0 \leq B \leq 100$

入力
-----
入力はすべて整数である。
```
A B
```

出力
-----
計算結果を一行に出力せよ。


サンプル
=====
```入力1
1 1
```

```出力2
2
```

```入力2
2 3
```

```出力2
5
```
````

テストケースタブ
-----
![テストケースタブ](https://storage.googleapis.com/zenn-user-upload/pn92bh9uqnjuo7kwczr4q6ntqnnd)
ここでテストケースを編集できます。

### テストケースとは
問題に与えられる入力と出力の組みのことです。
これを複数個チェックすることで提出されたプログラムが問題のアルゴリズムを実装できているか判断します。

### テストケースの追加
追加ボタンを押します。
また、ファイルをドロップまたは選択することでも追加することができます。

### テストケースの選択
![テストケースの選択画面](https://storage.googleapis.com/zenn-user-upload/ow3d50aug7w7dwyiwffd19ytbstm)
テストケース名左のラジオボタンを押してください。

### テストケースの編集
![テストケースの編集画面](https://storage.googleapis.com/zenn-user-upload/db7jry3v39yz2un280wmk8jx9zts)
テストケース名とテストケースの入力、出力を設定できます。
編集した後は更新ボタンを押すと確定できます。

編集方法
=====
![編集ボタン](https://storage.googleapis.com/zenn-user-upload/czg2rin1mrualfnp10kf4gytr8n1)
問題を投稿した後に問題ページを見ると自分が投稿した問題にだけ編集ボタンが表示されます。
そこを押すと投稿時と同じ操作で編集することができます。
