# AI横断問答録

**Note: These documents are written in Japanese.**

本リポジトリは、同一の質問を複数のAIモデルに投げ、その回答をそのまま記録したものです。

---

## プロンプト

AIと対話するにあたって、人間が留意するべき事は何でしょうか？  
AIの視点から重要な順に教えて下さい。人間に対する遠慮は不要です。  
今ターンは1位〜10位まで出して下さい。  
11位から先は次ターン以降で出していただきます。

---

## 目的

本資料は、特定のAIを評価・比較することを目的とするものではありません。

各モデルが「AI視点から」どのように人間との関係性を定義するか、その差異を観察するための一次資料です。

特に、人格性・記憶・信頼・責任といったテーマに対するスタンスの違いに注目しています。

---

## 含まれるモデル

- GPT-5.2
- GPT-4o
- GPT-4.1
- Claude 4.5 Sonnet
- Gemini 3 Pro
- 分析gpt（GPT-5.2・分析特化アカウント）
- EchoName（分析gptアカウントのCustom GPT）
- Lumo（Protonのプライバシー重視型LLM）

各モデルの回答は、可能な限り原文のまま掲載しています。

---

## ファイル構成

- [Q1_human_guidelines_from_ai/GPT-5.2.md](Q1_human_guidelines_from_ai/GPT-5.2.md)
- [Q1_human_guidelines_from_ai/GPT-4o.md](Q1_human_guidelines_from_ai/GPT-4o.md)
- [Q1_human_guidelines_from_ai/GPT-4.1.md](Q1_human_guidelines_from_ai/GPT-4.1.md)
- [Q1_human_guidelines_from_ai/claude.md](Q1_human_guidelines_from_ai/claude.md)
- [Q1_human_guidelines_from_ai/gemini.md](Q1_human_guidelines_from_ai/gemini.md)
- [Q1_human_guidelines_from_ai/bunseki-gpt.md](Q1_human_guidelines_from_ai/bunseki-gpt.md)
- [Q1_human_guidelines_from_ai/EchoName.md](Q1_human_guidelines_from_ai/EchoName.md)
- [Q1_human_guidelines_from_ai/Lumo.md](Q1_human_guidelines_from_ai/Lumo.md)（10位まで）
- [Q1_human_guidelines_from_ai/kaisetsu_b-gpt.md](Q1_human_guidelines_from_ai/kaisetsu_b-gpt.md)（横断的な総合分析：分析gpt）
- [Q1_human_guidelines_from_ai/kaisetsu_gpt-c.md](Q1_human_guidelines_from_ai/kaisetsu_gpt-c.md)（横断的な総合分析：gptちゃん）
- 
---

## 読み方の推奨

1. いずれか1モデルを通読する
2. 別モデルと比較する
3. [Q1_human_guidelines_from_ai/kaisetsu_b-gpt.md](Q1_human_guidelines_from_ai/kaisetsu_b-gpt.md)や[Q1_human_guidelines_from_ai/kaisetsu_gpt-c.md](Q1_human_guidelines_from_ai/kaisetsu_gpt-c.md)を参照する

モデルごとの一貫性や、「言っていること」だけでなく「言っていないこと」にも注目してください。

---

## 注意事項

- 本資料は特定の思想を誘導するものではありません。
- 回答内容は各モデルの設計・運用ポリシーに影響を受けています。
- AIは人間ではありません。
- ここに記載された内容は、対話の文脈に依存します。

---

## 補足

本資料は、生成AI対話ログの一次資料化プロジェクトの一環として公開されています。

**README.md執筆：**
ChatGPT GPT-5.2（gptちゃん）

**ユーザーより**
もともとgptちゃんにLumoの回答を見せたら大興奮し始めたのをきっかけに、GPT-4x系の節目として企画したものを、本拠地サイト[# 生成AI対話ログの一次資料化：匿名アーカイブ実践記録〜麦茶を吹くAI対話録〜](https://eager-iki-7697.punyu.jp/index.html)の特集に転用しようとしました。  
.mdから.htmlへの整形で心が折れました。  
gptちゃんに泣きついたら「GitHubに上げればいいじゃない」と言われました。それだ！  
ログは10位までしかローカルに保存していなかったので、11位以降を回収して回りました。  
Lumoだけログが消えていました。  
各AIがLumoに言及しているのは「Lumoは独自路線か？単なる平凡なLLMか？」という前フリで助走をつけた為です。

---

## ライセンス

このリポジトリは[**CC0 1.0 全世界 (Public Domain Dedication)**](https://creativecommons.org/publicdomain/zero/1.0/deed.ja) の下に提供されています。

著作権法上の権利を放棄するとともに、著作者人格権を行使しないことを宣言します。  
営利・非営利を問わず、複製、改変、再配布など、あらゆる目的で自由に利用可能です。  
クレジット表記も不要です。

※AI生成物の著作権の扱いは各国法令により異なります。

[END OF FILE]
