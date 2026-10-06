<!-- ELUCENIA technical documentation · escore-isquemico-de-hachinski · ja · no clinical/professional/rights approval -->

# Hachinski虚血スコア

[条件・出典・許諾](https://elucenia.org/ja/tools/escore-isquemico-de-hachinski)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 突然の発症

`abrupto`

### 階段状の悪化

`degraus`

### 変動する経過

`flutuante`

### 夜間の錯乱

`noturna`

### 人格の相対的保持

`personalidade`

### 抑うつ

`depressao`

### 身体愁訴

`somaticas`

### 情動失禁（情動不安定）

`labilidade`

### 高血圧の既往

`has`

### 脳卒中の既往

`avc`

### 動脈硬化合併の所見

`ateroscl`

### 局所神経症状

`sintomas`

### 局所神経徴候

`sinais`

## 方法の版

Hachinski 1975：13因子，合計0–18；Rosen短縮版ではない

## 記載された計算式

2点：急な発症，変動する経過，脳卒中既往，局所症状，局所徴候。1点：段階的悪化，夜間の錯乱，人格保持，うつ，身体的訴え，情動不安定，高血圧，動脈硬化。合計：0～18。

## 限界・対象集団

変性性認知症と多発梗塞性認知症の鑑別を支援します。混合型認知症では性能が低下しました。スコアは病因評価に代わるものではなく、公表された閾値は研究された集団と変法に属します。

## 参考文献

- [Hachinski VC et al. Cerebral blood flow in dementia. Arch Neurol, 1975.](https://doi.org/10.1001/archneur.1975.00490510088009)

- [Moroney JT et al. Meta-analysis of the Hachinski Ischemic Score in pathologically verified dementias. Neurology, 1997.](https://doi.org/10.1212/WNL.49.4.1096)

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

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

原発性変性認知症を示唆する（≤ 4点）

関連する血管性要素を除外しない：神経画像を確認する。


### 2

中間域（5～6点）：混合型認知症の可能性


### 3

血管性認知症を示唆する（≥ 7点）

神経画像で確認する（梗塞、小血管疾患）。

