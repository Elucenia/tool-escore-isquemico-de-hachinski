<!-- ELUCENIA technical documentation · escore-isquemico-de-hachinski · zh · no clinical/professional/rights approval -->

# Hachinski 缺血评分

[条件、来源与许可](https://elucenia.org/zh/tools/escore-isquemico-de-hachinski)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 突然起病

`abrupto`

### 阶梯式恶化

`degraus`

### 波动性病程

`flutuante`

### 夜间意识混乱

`noturna`

### 人格相对保留

`personalidade`

### 抑郁

`depressao`

### 躯体主诉

`somaticas`

### 情绪失控（情绪不稳）

`labilidade`

### 高血压史

`has`

### 卒中史

`avc`

### 伴随动脉粥样硬化证据

`ateroscl`

### 局灶性神经症状

`sintomas`

### 局灶性神经体征

`sinais`

## 方法版本

Hachinski 1975：13项因素，总计0–18；非Rosen缩减版

## 已记录的公式

2分：突然起病、波动病程、卒中史、局灶症状、局灶体征。1分：阶梯式恶化、夜间意识混乱、人格保留、抑郁、躯体主诉、情绪不稳、高血压、动脉粥样硬化。总计：0至18。

## 限制与适用人群

用于辅助区分退行性痴呆与多发梗死性痴呆。在混合性痴呆中的表现较差。评分不能代替病因评估；发表的阈值属于各自研究的人群及变体。

## 参考文献

- [Hachinski VC et al. Cerebral blood flow in dementia. Arch Neurol, 1975.](https://doi.org/10.1001/archneur.1975.00490510088009)

- [Moroney JT et al. Meta-analysis of the Hachinski Ischemic Score in pathologically verified dementias. Neurology, 1997.](https://doi.org/10.1212/WNL.49.4.1096)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
