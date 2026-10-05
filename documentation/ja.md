<!-- ELUCENIA technical documentation · indice-tornozelo-braquial · ja · no clinical/professional/rights approval -->

# 足関節上腕血圧比（ABI）

[条件・出典・許諾](https://elucenia.org/ja/tools/indice-tornozelo-braquial)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 右上腕収縮期血圧

`bd`

mmHg · 範囲: 50–300

### 左上腕収縮期血圧

`be`

mmHg · 範囲: 50–300

### 右足関節の最高収縮期圧（後脛骨・足背動脈）

`td`

mmHg · 範囲: 0–350

### 左足関節の最高収縮期圧（後脛骨・足背動脈）

`te`

mmHg · 範囲: 0–350

## 方法の版

AHA 2012：ABI=足関節最高収縮期血圧/上腕最高収縮期血圧；両下肢で低いABI

## 記載された計算式

各下肢のABI=その足関節の最も高い収縮期血圧÷両上腕で最も高い収縮期血圧。患者のABIは左右のうち低い値です。

## 限界・対象集団

各脚について同側足関節の最も高い収縮期血圧と、両上腕のうち最も高い血圧を用いて計算し、それらの平均を使用しないでください。糖尿病や慢性腎臓病で多い非圧縮性動脈は指数を見かけ上高くし、追加評価が必要になることがあります。安静時の正常値はすべての虚血を除外せず、慢性下肢切迫虚血ではこの指数だけでは不十分な場合があります。ツールは適切な測定法、症状、血管診察、追加検査の代わりにはなりません。

## 参考文献

- [Aboyans V et al. Measurement and interpretation of the ankle-brachial index: a scientific statement from the American Heart Association. Circulation, 2012.](https://doi.org/10.1161/CIR.0b013e318276fbcb)

- [Gerhard-Herman MD et al. 2016 AHA/ACC Guideline on the Management of Patients With Lower Extremity Peripheral Artery Disease. Circulation, 2017.](https://doi.org/10.1161/CIR.0000000000000471)

- [AHA/ACC2024 lower-extremity PAD guideline](https://www.ahajournals.org/doi/full/10.1161/CIR.0000000000001251)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
