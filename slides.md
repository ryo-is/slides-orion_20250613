---
theme: dracula
---

# 生成AIとエンジニアの仕事と私~実践知を添えて~

2025/06/13 【ORION × スマレジ共催】生成AI時代に考えるエンジニアのキャリア会議

---
layout: author
---

![icon](./images/icon.png)

## いずりょー / is_ryo 

#EngineeringManager@Sprocket

#TypeScriptが好き #JavaScriptは嫌い

#kansai.ts Organizer

#フロントエンドカンファレンス関西実行委員

X → @is_ryo

---
layout: section
---

# 生成AI活用してますか？

---
---

# 簡単にアンケート取りたい

<div text-2xl>

1. あまり活用できていない…

2. 少し質問するくらいで使っている

3. 開発業務に取り入れている(Copilot, Clineなど)

4. それ以外の業務にも取り入れている(資料作成など)

5. 生成AIないと生きていけないっ！！！(仕事できない)

</div>

---
---

# ちなみに私は…

<div text-2xl>

1. あまり活用できていない…

2. 少し質問するくらいで使っている

3. 開発業務に取り入れている(Copilot, Clineなど)

4. それ以外の業務にも取り入れている(資料作成など)

<div font-bold underline>5. 生成AIないと生きていけないっ！！！(仕事できない)</div>

</div>

<br />

<div font-bold text-4xl >
生成AI取り上げられたらエンジニア辞めちゃうんじゃないかというくらい、生成AIが仕事と強く依存している
</div>

---
---

# 弊社の生成AI事情

<div text-2xl>

- <div leading-relaxed>主にClaude、Geminiを利用している</div>

  - <div leading-relaxed>エンジニアだけでなく非エンジニアも一定数活用している</div>

  - <div leading-relaxed>エンジニアはRooCode、ClaudeCodeとか、非エンジニアはClaudeのWebアプリとか</div>

  - <div leading-relaxed>ClaudeProjectを活用して生成AIアプリみたいなものを作っている</div>

- <div leading-relaxed>コーディング作業はすべてRooCodeに任せるべく試行錯誤中</div>

- <div leading-relaxed>Devinにより技術的負債の解消を実験的に行っている</div>

- <div leading-relaxed>社内外向けに生成AIエージェントの開発をしている</div>

  - <div leading-relaxed>社内向けは割と実験場として好き勝手やっている</div>

  - <div leading-relaxed>生成AIプロダクトの開発を進めている</div>

</div>

---
layout: center
---

<div font-bold text-5xl leading-relaxed>今日は私自身の経験談からお話します。<br />※すべて個人の意見です。</div>

---
layout: center
---

<div font-bold text-5xl leading-relaxed>エンジニアとしての仕事が<br/>どう変わったか？</div>

---
---

# エンジニアとしての仕事がどう変わったか？

<div text-2xl>

1. コードを(ほぼ)書かなくなった

2. レビューの時間が減った

3. 設計も生成AIとやるようになった

4. 新しい知見を生成AI経由で得るようになった

5. 生成AIをどう活用すると効果的か考えることに時間を使うようになった

</div>

---
---

# コードを(ほぼ)書かなくなった

<div text-2xl>

- <div leading-relaxed>何よりアウトプットを出す速度が早すぎるので、コードを書くという作業は人間がやる必要がなくなった</div>

- <div leading-relaxed>最初は一つの関数とかテストとか一部のコードを書いてもらう程度だったが、この半年でかなり賢くなったので、もうアプリケーション丸ごと任せられるくらいになっている</div>

- <div leading-relaxed>エンジニアじゃなくてもPoCレベルのアプリケーション作れちゃう世界が来ている</div>

  - <div leading-relaxed>例) 弊社のPdMは非エンジニアだが、週に1,2個くらいプロトタイプ作ることが可能になっていた</div>

</div>

---
---

# レビューの時間が減った

<div text-2xl>

- <div leading-relaxed>一次レビューは生成AIに任せるようになってきた</div>

- <div leading-relaxed>ある意味機械的に判断できるような指摘内容は生成AIがしてくれるので、その前提で人間がレビューできるようになった</div>

  - <div leading-relaxed>BiomeでLintとFormatして生成AIでの一次レビューが通ってから、人間がレビューする</div>

- <div leading-relaxed>コード規約や設計思想など、開発組織で定めているルールをコンテキストとして生成AIに渡して、どういう観点でレビューしてほしいかをプロンプトで書いて、チューニングしてを繰り返している</div>

- <div leading-relaxed>これがプロンプト芸、否、プロンプトエンジニアリングか…となっている</div>

</div>

---
---

# 設計も生成AIとやるようになった

<div text-2xl>

- <div leading-relaxed>アプリケーションの設計も生成AIとやるようになった</div>

- <div leading-relaxed>まず設計書に重要なことを書いて、生成AIに校閲してもらう</div>

- <div leading-relaxed>インターネットに転がっているプラクティスを参照して、様々なパターンを提案してくれる。しかも非現実的な速度で…</div>

- <div leading-relaxed>生成AIに設計書を作らせて、それを次のタスクに渡してアプリケーションを実装させることをよくやっている</div>

</div>

---
---

# 新しい知見を生成AI経由で得るようになった

<div text-2xl>

- <div leading-relaxed>先程の話にもつながるが、ふとしたタイミングで自分の知らない知見を得る機会が増えた</div>

  - <div leading-relaxed>新しい言語やフレームワークなどの知見</div>

  - <div leading-relaxed>クラウドサービスなどのアップデート情報</div>

- <div leading-relaxed>半年前に比べて生成AIが参照できる情報の鮮度・精度が上がってきている</div>

  - <div leading-relaxed>Web検索するのが当たり前になってきた</div>

</div>

---
---

# 生成AIをどう活用すると効果的か考えることに時間を使うようになった

<div text-2xl>

- <div leading-relaxed>人間の生産性は生成AIによって爆発的に向上した</div>

- <div leading-relaxed>が、生成AI自体の生産性ももっと上げられると掛け算的に全体的な生産性が向上できそう</div>

- <div leading-relaxed>ということで生成AIの生産性みたいなことを考えるようになってきた</div>

- <div leading-relaxed>プロンプトでどんな情報を投げるか、どこまでのコンテキストを持たせておくべきかみたいなことを考えながら試行錯誤している</div>
  
</div>

---
layout: center
---

<div font-bold text-5xl leading-relaxed>これからどういう<br />エンジニアが求められるか</div>

---
---

# エンジニアとしての仕事がどう変わったか？

<div text-2xl>

1. コーディング力よりも設計力

2. 高い表現能力、言語化能力

3. 生成AIを活用した業務・組織設計力

4. 生成AIについての高い理解度

</div>

---
---

# コーディング力よりも設計力

<div text-2xl>

- <div leading-relaxed>コードを書く能力では勝てない…ので任せた方がいい</div>

  - <div leading-relaxed>うまく対応できない言語、フレームワークはあるが、大半はうまく対応してくれる</div>

- <div leading-relaxed>ただ生成AIは自立して何もないところから生み出すことはできない</div>

  - <div leading-relaxed>何かしらのトリガーがないと動き出さない</div>
  
  - <div leading-relaxed>人間がどんなアウトプットを期待しているのかを伝えてあげないといけない</div>

- <div leading-relaxed>生成AIにどんなものを作って欲しいのかという情報を、曖昧さを可能な限り排除した上でプロンプトを投げられるようにならないといけない</div>

</div>

---
---

# 高い表現能力、言語化能力

<div text-2xl>

- <div leading-relaxed>生成AIは人間から渡されたプロンプトから、期待されるアウトプットを生成してくれる</div>

  - <div leading-relaxed>要するに入力として渡すプロンプトの質が重要</div>

- <div leading-relaxed>プロンプトの質を上げるためには極論「生成AIが毎回同じ理解をしてくれるような明確な情報、曖昧さを排除した情報」を書く必要がある</div>

  - <div leading-relaxed>期待するアウトプットについてうまく表現、言語化できないといけない</div>

  - <div leading-relaxed>プロンプトの質で生成AIのアウトプットの質が大きく変わってくる</div>
</div>

---
---

# 生成AIを活用した業務・組織設計力

<div text-2xl>

- <div leading-relaxed>ただ生成AIを使うだけでなく、業務や組織に組み込むようなアクションが取れると、組織として強くなれる可能性がある</div>

  - <div leading-relaxed>エンジニアの作業を代行する生成AIエージェントを作る</div>

  - <div leading-relaxed>コーディング業務はもうDevinやClaudeCodeActionに任せて非同期で作業させる</div>

- <div leading-relaxed>これはマネジメント領域に関わってくるかも知れないが、マネージャーでなくても生成AIの力で組織設計の一端を担うことができるという可能性がある</div>

  - <div leading-relaxed>生成AIを活用した組織としての生産性向上の施策を考えている</div>

</div>

---
---

# 生成AIについての高い理解度

<div text-2xl>

- <div leading-relaxed>生成AIはどんな仕組みで動いていて、どういう設計思想で設計されていて、何ができて何ができないのか、何が得意で何が不得意なのかなど知っていると、生成AIを活用できるレベルがグッと上がる</div>

- <div leading-relaxed>書籍、論文、できる人とのコミュニケーション、まずは使ってみるなどでどんどん知見、経験値を貯めにいった方がいい</div>

  - <div leading-relaxed>書籍は原理原則を説明しているようなものがおすすめ</div>

  - <div leading-relaxed>ユースケースの紹介みたいなものはすぐに陳腐化してしまう</div>

</div>

---
---

# まとめ

<div text-2xl>

- <div leading-relaxed>生成AIはエンジニアの仕事をなくすものではなく、変えるもの</div>

- <div leading-relaxed>怖がって近寄らないのではなくて、寄り添っていこう</div>

- <div leading-relaxed>相手(生成AI)のことを知って、どんな言葉を届けるとより良い仕事をしてくれるのかを考えてあげよう</div>

  - <div leading-relaxed>人間関係と近しいものがある</div>

- <div leading-relaxed>これからエンジニアの仕事や価値というのはどんどん変わっていくだろうし、その波に乗れる気持ちを持っておくことが大事</div>

  - <div leading-relaxed>乗るしかない、このビックウェーブに…</div>

- <div leading-relaxed font-bold>今回は表面的な話に絞ったので、もっと深い話をしたい！なので懇親会で話しましょう！</div>

</div>

---
layout: center
---

<div font-bold text-5xl leading-relaxed>Thanks!!!</div>
