---
title: "Zipファイルでの投稿のやり方"
---
:::message
各用語の解説は前チャプターを参照してください。
:::
投稿方法
=====
```text:Zipファイルの中身
/
├── testcases
│   ├── in
│   │   └── testcase-1.txt
│   └── out
│       └── testcase-1.txt
├── problem.json
└── README.md
```
☝️のような構造のZipファイルを[問題を投稿](https://mojacoder.vercel.app/problems/post)から選択してアップロードしてください。

[実際のZipファイル](https://www.dropbox.com/s/az3eft0i0ckjgc5/a-plus-b.zip?dl=0)

Zipファイルの名前が`問題Slug.zip`になります。
例えば問題Slugを`a-plus-b`にしたいときは`a-plus-b.zip`にしてください。

:::message alert
testcasesやproblem.json、README.mdは必ずZipファイル直下に置いてください。
:::

各ファイル・フォルダの意味
-----
### testcases
各テストケースを配置します。
テストケースの入力をinディレクトリ、出力をoutディレクトリに同じファイル名で配置してください。

### problem.json
問題の設定をここでします。
現状はタイトルしかいじレません。
```json:problem.json
{
    "title": "問題タイトル"
}
```

### README.md
問題文をMarkdown記法で記述します。
数式はTex記法で書くことができます。

編集方法
=====
投稿した時と同じファイル名でZipファイルをアップロードしてください。

既存の問題のZipをダウンロード
=====
![Zipダウンロード](https://storage.googleapis.com/zenn-user-upload/hp23yq22k167i2jxhh4gl3zz8i5v)
問題の編集画面の現在のZipファイルをダウンロードを押してください。
