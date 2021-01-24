---
title: "非情報科高専生がAtCoder水色になるまでの一年間の振り返り。"
emoji: "🐎"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["AtCoder"]
published: true
---
一年かけてついにAtCoder水色に！
=====
今月中に達成するのが目標だったので良かったです。
ほぼ一年かかってしまいました……
https://twitter.com/makutamoto/status/1352984216607199232

当日のコンテストの振り返り
=====
ABCDEの5完でした。
DのDPの遷移式を間違い１ペナしたのは痛かったですが、E問題が解けたことで過去２番目のパフォーマンスで入水することができました。

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/582655/32c4f450-73be-dc9b-2578-740a800dd687.png)
![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/582655/819d80f9-d5d2-2003-54c8-be2a259a20b8.png)

自己紹介
=====
とある高専の電気電子工学科の３年生です。
数学力については、公式暗記で乗り切ってきたので多分身についてないと思います。
トランプやオセロなどの数学力を要求されるゲームは不得意で、ボタン連打で勝てるレベルのRPGしかできません。

開発系のプログラミングだけは長いことやっているのである程度はできます。
宣伝ですが最近は競技プログラミングの問題を自由に投稿できるサイト、MojaCoderを開発しているので使ってくれると嬉しいです。
👉 [リンク](https://mojacoder.vercel.app/problems)
👉 [GitHub](https://github.com/makutamoto/mojacoder)
予算の都合上、ジャッジが遅いですが多めにみてください。

AtCoderを始めたきっかけ
=====
AtCoderを始めたのは2020年3月1日です。
なんとなく2月にTwitterを始めてみて、強い人がよくBioにAtCoder何色と載せていたので興味を持ちました。
そしたら、同学年の情報科の人のBioにもAtCoderの色が書いてあったのでその人にどういうサイトか教えてもらい、登録してみました。

ちなみに最初はAtCoder灰色ってかなり上の方の色だと思ってました。灰色ってなんか強そうなので。

初コンテスト
=====
初参加はABC157でABCの3完、レートが27つきました。
![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/582655/cc1796a2-bc98-953c-cdd3-1cbcce5a7410.png)
なんとかCをACできたというのが伝わってきますね……
Dが水Diffな回は初心者には厳しかったように思えます。
![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/582655/8cb20424-924d-564e-6bb1-931ab10ec63d.png)

茶色になるまで（３月から５月）
=====
![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/582655/4f4a2ef7-7aad-5a77-ce11-d0b21ac97dae.png)
👆の画像の作成には[AtCoder Rollback](https://phocom.github.io/atcoder-rollback/index.html)を使いました。色変記事を書く時にかなり便利ですね。

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/582655/b00c07a2-acbe-a1b2-4122-c64b557c7abb.png)

レート遷移グラフをみるとわかるように茶色になるまで結構時間がかかっています。
これはヒートマップからもわかるように、コンテストの時のみ問題を解きまともなUpSolveすらしていなかったからでしょう。
さすがにこれでは得るものがないなと思い、４月の始めに休校の延長が決定してからAtCoder Problemsの有志バチャを用いて精進するようになってからレートが伸びるようになりました。

緑になるまで（５月から９月）
=====
![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/582655/e8fdbe43-5403-5e64-8a9c-1dd66f64fe18.png)
![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/582655/caf3247f-8ab3-b683-6edd-dbdf171b2f25.png)
４ヶ月かかりました。
これはヒートマップからわかるように主に対面授業が始まり、登下校の時間や睡眠時間の増加によって精進の時間がとれない日が増えてきたことが大きいと思っています。
また、後述しますが自分のレベルにあっていない問題を解きすぎてしまったのも悪かったと思いますね。

AtCoder Problemsにコミットしたり、下記のAtCoder系ツールを作っていたのはこの時でした。

- [AtCoder相性診断](https://github.com/makutamoto/atcoder-aisho-shindan)
- [AtCoder Badges](https://github.com/makutamoto/atcoder-badges)

水色になるまで（９月から１月）
=====
![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/582655/63a90773-9b93-3fa5-3803-7d40a1b8ee77.png)
![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/582655/6cc43adf-9700-e64b-9467-b970c6a828b8.png)
茶色での停滞を反省して高難易度の問題をちゃんと埋めるようにしたため、緑中位までは思ったより早く上がることができました。
主にメモ化再帰やDPの考え方が自分の中でしっかり身についたのが大きかったと思います。
ただ11月からかなりサボったので少し停滞しましたが、ABCの傾向が変わったことによりE問題まで安定して解けるようになったのが入水に大きく貢献したと思います。

### この時に開発していたもの
- [AtCoder Twitter Profile Updater](https://github.com/makutamoto/atcoder-twitter-profile-updater)
- [MojaCoder](https://github.com/makutamoto/mojacoder)

水色になるまでに覚えたもの
=====
- 累積和、尺取り法、imos法
- 二部探索
- Bit全探索
- UnionFind、DFS、BFS、ワーシャルフロイド、ダイクストラ法
- メモ化再帰、DP
- modint
- BIT
- 最大流、最小費用流

漏れてるものもあるとは思いますが、かなり勉強をサボっているので覚えたアルゴリズムはあまり多くはありませんし、蟻本も積んでいます。
modintやBITや最大流、最小費用流を扱えるようになったのはACLC2の中止により開催されたACLBCの存在が大きいと思います。
急なRatedに対応するためにACLPCを解いたことで便利な道具たちの使い方を覚えることができました。

なぜ水色になるのに一年もかかったのか
=====
![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/582655/83918f3b-efa6-1fde-d293-5e66a3026b6f.png)
ほぼすべてのRatedに参加して水色になるのに一年かかるのは、そこそこ時間かかってる方だと思います。
原因はやはり過去問をDifficultyでソートして、下から埋めてしまったことでしょう。
自分が到達したいレート帯の問題を解くようにしてからレートが上昇してくれるようになったことからも、レートを上げるのに重要なのはやはり量ではなく質だと思いました。

AtCoderを１年生の頃に始めておけばよかった
=====
「AtCoderを始めたきっかけ」のところに登場する情報科の人ですが、僕が１年生の時に一度AtCoderに誘ってくれてるんですね。
そこで話を聞いて、なんとなく退屈そうだなと思って断った自分を今は殴り飛ばしたいと思っています。
こんな後悔をする人をこれ以上増やさないために、AtCoderは広告をしっかりしてください。

AtCoderを始めて何が良かったか
=====
個人的にAtCoderを始めて良かったと感じたことは主に２つあります。
逆に悪かったことは特にありませんね。
コンテストの時間帯も自分には不都合ありませんでしたし。

#### 複雑な実装するのに１時間ぐらいかかっていたような実装を数分でできるようになった。
これはコンテストで鍛えられるので当然ですね。コンテストは週１であるので実力も落ちにくいですし。

#### 競技プログラミングに関連したツールを開発すると多くの人に使ってもらえるので開発モチベーションが向上した。
競技プログラミング自体というよりは界隈がすばらしいと思います。
今まで開発して、UIだけメインの機能だけ設計だけで満足してどうせこんなの使われないだろうなと思って開発を放棄したプログラムや完成しても使われなかったプログラムがたくさん僕のハードディスクに眠っています。
ところが、競プロ界隈向けに開発すると多くの人が使って拡散してバグ報告までしてくれるのでかなりモチベーションを維持して開発できるようになりました。
これは開発系の高専生にはAtCoderを始めて競技プログラミング界隈に属する十分なメリットだと思います。

最後に
=====
AtCoderを身の回りの人にも布教していますが、なかなか面白さが伝わらなくて難航しています。
簡単に始められて実になるコンテンツなのでもっと多くの人に始めてほしいですね。

それでは最後に、
AtCoder最高！一番好きなプログラミングコンテストサイトです！
