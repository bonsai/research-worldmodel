# LLMの歴史
## ――言語を機械に渡すまで

LLM（Large Language Model）の歴史は、突然AIが生まれた歴史ではない。

それはむしろ、**人間が世界を区別し、言葉にし、文字にし、データにし、機械に学習させていった歴史**である。

---

## 1. 世界を区別する

LLMよりはるか以前から、人間は世界を区別していた。

これは石。

これは火。

これは獲物。

これは仲間。

これは危険。

まだ「データ」も「AI」もない。

しかし、

```text
WORLD
 ↓
DIFFERENCE
 ↓
DISTINCTION
```

という最初の操作がある。

世界の中から差異を見つける。

そして、その差異を他者と共有する。

---

## 2. 名前をつける

差異が共有されるようになると、名前が生まれる。

```text
Difference
 ↓
Distinction
 ↓
Sign
 ↓
Word
```

「火」という音や記号そのものが火なのではない。

しかし、その記号によって、他者と同じものを指し示せる。

ここから人間の世界は、**記号によって共有される世界**になっていく。

---

## 3. 文字が記憶になる

話された言葉は消える。

文字は残る。

これが大きな転換だった。

```text
Human Experience
 ↓
Language
 ↓
Writing
 ↓
Text
 ↓
Accumulated Knowledge
```

知識が個人の記憶から外部化される。

世代を越えて保存される。

図書館ができる。書物ができる。

そして最終的に、**大量の言語データ**が生まれる。

---

## 4. 数学が言語を記述し始める

20世紀になると、人間は言語を数学的に扱おうとする。

文法。論理。確率。情報。

ここで言語は、単なる文学や会話だけではなく、**計算可能な対象**になっていく。

---

## 5. Turing ― 機械は言語を扱えるか

1950年、Alan Turingは「Computing Machinery and Intelligence」を発表した。

重要なのは、「機械は本当に考えているのか？」という問いを、**機械と人間の対話**という形に置き換えたことだった。

```text
Human
  ↕
Language
  ↕
Machine
```

ここで言語は、知能を観察するためのインターフェースになった。

---

## 6. Symbolic AI ― 人間がルールを書く

1950〜60年代。

AI研究では、「知識を記号として機械に与えれば、推論できるのではないか」という考え方が強くなる。

```text
World
 ↓
Human Knowledge
 ↓
Rules
 ↓
Symbols
 ↓
Machine Reasoning
```

論理、ルール、文法、専門知識。

人間が世界をどう理解しているかを、明示的に記述しようとした。

しかし問題があった。

**世界は、書いたルールより複雑だった。**

---

## 7. Statistical NLP ― 言語を確率として見る

1980〜90年代。

大きな転換が起こる。

「この単語の次には何が来やすいか？」という問題を、確率として扱う。

```text
P(word | context)
```

言語を、ルールの集合ではなく、**大量の例から推定できる確率分布**として見る。

これは後のLLMにつながる非常に重要な思想だった。

---

## 8. Internet ― 言語データが爆発する

1990年代後半〜2000年代。

インターネットが普及する。

Webページ、掲示板、ニュース、Wikipedia、ブログ、コード、電子書籍。

人間が書いた文章が、巨大な規模で蓄積されていく。

```text
Human Activity
 ↓
Internet
 ↓
Text
 ↓
Corpus
 ↓
Training Data
```

ここで初めて、**「言語を大量に機械へ渡す」**ことが現実的になる。

---

## 9. Neural Networks ― ルールを書くのをやめる

ニューラルネットワークによって、人間がすべてのルールを書く必要がなくなっていく。

単語を直接「意味のある記号」として扱うのではなく、ベクトルとして表現する。

```text
Word
 ↓
Vector
 ↓
Representation
```

すると、似た使われ方をする言葉が、数学的な空間の中でも近くなる。

言語の構造が、モデル内部に分散して表現され始める。

---

## 10. Word2Vec ― 単語ではなく関係を学ぶ

2013年のWord2Vecは、単語そのものではなく、**単語がどのような文脈で使われるか**から表現を学習した。

「意味を辞書として与える」のではなく、**使用から関係を学ぶ**という方向への転換だった。

---

## 11. Attention ― 文脈を見る

2014〜2016年。

Attentionという考え方が重要になる。

文章の中で、「今の単語を理解するために、どの部分を見るべきか？」を学習する。

```text
Token
 ↓
Context
 ↓
Attention
 ↓
Representation
```

言語モデルは、単語を一個ずつ見るだけではなく、**文脈の関係**を見るようになる。

---

## 12. 2017 ― Transformer

2017年、論文 **“Attention Is All You Need”** によってTransformerが登場する。

これが現代LLMの大きな転換点になる。

Transformerは、大量の文章を効率よく扱い、文脈上の関係を学習できる。

```text
Text
 ↓
Tokens
 ↓
Embeddings
 ↓
Attention
 ↓
Transformer
 ↓
Representation
```

---

## 13. GPT ― 次のTokenを予測する

GPT系のモデルでは、非常に単純な形式の学習が中心になる。

```text
Given:
"The cat is on the"

Predict:
"mat"
```

つまり、**次に来るTokenを予測する。**

数学的には、

```text
P(tokenₙ | token₁ ... tokenₙ₋₁)
```

を学習する。

---

## 14. Scaling ― 大きくすると何が起こるか

ここからLLMの時代が始まる。

モデル、データ、計算量を大きくする。

```text
Model Size
Data Size
Compute
   ↓
Scale
   ↓
Capability
```

人間が一つ一つ能力をプログラムしたわけではない。

大量の言語データから、言語の構造を学習させる。

---

## 15. LLMは何を学んでいるのか

LLMは単に「文章を暗記している」だけなのだろうか？

大量の文章から、概念、関係、文法、世界についての記述、人間の推論パターン、コード、物語、会話などを内部表現として獲得する。

```text
Text
 ↓
Statistical Structure
 ↓
Representation
 ↓
Generation
```

---

## 16. Instruction Tuning ― 会話する機械へ

基礎モデルは「次のTokenを予測する機械」だった。

しかし、それだけでは人間にとって使いやすくない。

そこで、指示に従うように学習する。

```text
User
 ↓
Instruction
 ↓
LLM
 ↓
Response
```

LLMが、**言語生成器**から**人間とのインターフェース**へ変わっていく。

---

## 17. ChatGPT ― 言語モデルが一般ユーザーの前に出る

2022年以降、大規模言語モデルが一般ユーザーにも広く使われるようになる。

ここで重要な変化がある。

LLMは、研究室のモデルではなく、**人間が直接話しかける知的インターフェース**になる。

```text
Human
 ↕
Language
 ↕
LLM
```

---

## 18. LLMからAgentへ

しかし、言葉を生成するだけでは、世界を変えられない。

そこで、Tools、Memory、Sensors、APIs、Computers、Robots、Filesystem、Browserなどと接続する。

```text
LLM
 ↓
Think
 ↓
Tool
 ↓
Action
 ↓
Outcome
 ↓
Observation
 ↓
LLM
```

ここでLLMは、**Agentの中核コンポーネント**になり始める。

---

## 19. LLMとWorld

しかし、ここで根本的な問いが残る。

LLMが直接見ているのは、「世界そのもの」なのか？

そうではない。

LLMが主に学習しているのは、**人間が世界について残した記号的痕跡**である。

```text
WORLD
 ↓
HUMAN
 ↓
COGNITION
 ↓
LANGUAGE
 ↓
TEXT / CODE
 ↓
DATA
 ↓
LLM
```

だからLLMは、世界そのものというより、**言語によって表現された世界の巨大なモデル**として考えることができる。

---

## 20. View-Based World Modelへの接続

ここで、

```text
Physical
 ↓
Interface
 ↓
Cognition
 ↓
Data
 ↓
Symbolic
```

という見方が重要になる。

LLMは主に、

```text
Cognition
 ↓
Symbolic
 ↓
Data
 ↓
Model
```

という側から世界を学習している。

一方、ロボットは、

```text
Physical
 ↓
Interface
 ↓
Cognition
 ↓
Action
 ↓
Physical
```

というループを持つ。

したがって、**LLM = Worldそのもの**と考える必要はない。

LLMは、**WorldのあるViewを学習したModel**として位置づけられる。

---

## 21. 次の段階 ― 世界へ戻る

LLMがツールや身体を持つと、ループが閉じ始める。

```text
WORLD
 ↓
INTERFACE
 ↓
COGNITION
 ↓
LANGUAGE
 ↓
LLM
 ↓
DECISION
 ↓
ACTION
 ↓
WORLD
 ↺
```

LLMは単なる文章生成器ではなくなる。

世界を観測し、問いを作り、考え、行動し、結果を観測する。

---

## 22. Genesis

LLMの歴史を一つの流れにすると、

```text
WORLD
 ↓
DIFFERENCE
 ↓
DISTINCTION
 ↓
SIGN
 ↓
LANGUAGE
 ↓
WRITING
 ↓
TEXT
 ↓
DATA
 ↓
STATISTICS
 ↓
NEURAL NETWORK
 ↓
REPRESENTATION
 ↓
TRANSFORMER
 ↓
LLM
 ↓
AGENT
 ↓
ACTION
 ↓
WORLD
 ↺
```

つまりLLMのGenesisは、Transformerから始まったのではない。

もっと古い。

---

## 23. 本当のGenesis

始まりは、人間が世界の中から、**「違い」を見つけたこと**だったのかもしれない。

違いを区別した。

区別に名前をつけた。

名前を言語にした。

言語を文字にした。

文字をデータにした。

データを統計的に扱った。

ニューラルネットワークに学習させた。

Transformerによって文脈を扱った。

LLMが言語を生成するようになった。

そして今、LLMは再び世界へ戻ろうとしている。

---

## 24. そして問いが残る

```text
WORLD
 ↓
LANGUAGE
 ↓
DATA
 ↓
MODEL
 ↓
LANGUAGE
 ↓
ACTION
 ↓
NEW WORLD
 ↓
NEW LANGUAGE
 ↺
```

問いは、「LLMは人間のように考えるのか？」だけではない。

もっと根本的には、

> **「世界を表現したモデルが、世界に作用し始めたとき、モデルと世界の関係はどう変わるのか？」**

である。

そして、その問いから、次のWorld Model研究が始まる。
