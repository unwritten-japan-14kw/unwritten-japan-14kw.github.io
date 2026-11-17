# Japan, Unwritten — 記事のルール

## 1. 自然な英語で書く(AI翻訳らしさをなくす)

- 短縮形を使う(it's / you'll / don't)。会話のトーンで書く
- 具体的に書く。金額、時期、場所、実際のシーンを入れる
- 一文を短く。長い文は2つに分ける
- 以下の「AIっぽい」表現は使わない
  - delve into / navigate / in today's world / it's important to note that
  - Whether you're A or B, ... で始める導入
  - "Not only... but also" の多用、何でも3つ並べる癖
  - seamless / robust / unlock / embark / tapestry / bustling / vibrant
  - ダッシュ(—)の多用
  - 結びの "In conclusion" や、感想めいたまとめ
- 日本語の直訳を避ける(例:「〜することが大切です」→ It's important to... と書かず、何をすればいいかを直接書く)
- 日本語の用語は、最初に出たとき「英語の説明 + 日本語 + ローマ字」で示す
  例:resident tax (住民税, *jūminzei*)

## 2. 重要な箇所は色を変える

| 種類 | 色 | 使う場面 |
|---|---|---|
| Warning(注意) | 赤 | お金を失う、トラブルになる、法的な問題 |
| Key point(要点) | 黄色のマーカー | 記事の中で一番覚えてほしい一文 |
| Tip(コツ) | 緑 | 知っていると得をする、楽になる |
| Japanese term(日本語) | 青 | 窓口で見せたり言ったりする日本語 |

- 1記事あたり、色付きは合計5〜8か所まで。多すぎると目立たなくなる
- 書き方(サイト用):
  - 要点:`<mark>…</mark>`
  - 日本語:`<span class="jp">住民税</span>`
  - ボックス:`<div class="tip" markdown="1">` / `<div class="warning" markdown="1">` の中で、本文の先頭に
    `<strong class="label">Tip<span class="c">:</span></strong>` または
    `<strong class="label">Watch out<span class="c">:</span></strong>` を入れる
    (ラベルを本文として入れることで、Medium に取り込んでも「Tip:」「Watch out:」が残る)

## 3. 記事の型

1. The scene(戸惑うシーン)
2. What is it?(それは何か)
3. Why it works this way(日本側の理屈)
4. What to do(チェックリスト)
5. Why Japanese people don't mention it(日本人が説明しない理由)
6. FAQ
7. 免責文と最終更新日

## 4. Medium への転載

- Medium の「Import a story」で取り込む(canonical link が自動で入る)
- 表は崩れるので、記事ごとに「表の置き換え文」を用意する
- 赤・緑のボックスは Medium の引用ブロックにする(ラベルは自動で入るので、段落を選んで「"」を1回押すだけ)
- 末尾にサイトへの誘導文を入れ、「Originally published at」は消さない

## 5. 検索キーワード

- 書く前に、狙う検索語を1つ決める(例:resident tax Japan)。記事の先頭の `keyword:` に記録する
- その検索語を、タイトル、説明文(description)、見出しの1つ以上に入れる
- 外国人向けの記事では「foreigner」「in Japan」など、実際に検索で使われる言葉を入れる
- 見出しは自然な英語を保ちつつ、「What to bring」のような一般的な言葉だけにしない
- 一度公開した記事のURLは変えない
- サイトは検索向けのタイトル、Medium は読者の興味を引くタイトル、と使い分けてよい
- 候補の探し方:Google のサジェスト、公開後は Search Console の検索パフォーマンス
- 記事どうしのリンクは `[文]({{ site.url }}{% post_url ファイル名 %})` と書き、完全なURLにする(Medium に取り込んでもリンクが切れないように)
