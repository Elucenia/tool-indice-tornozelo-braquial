<!-- ELUCENIA technical documentation · indice-tornozelo-braquial · zh · no clinical/professional/rights approval -->

# 踝肱指数（ABI）

[条件、来源与许可](https://elucenia.org/zh/tools/indice-tornozelo-braquial)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 右臂收缩压

`bd`

mmHg · 范围: 50–300

### 左臂收缩压

`be`

mmHg · 范围: 50–300

### 右踝最高收缩压（胫后或足背动脉）

`td`

mmHg · 范围: 0–350

### 左踝最高收缩压（胫后或足背动脉）

`te`

mmHg · 范围: 0–350

## 方法版本

AHA 2012：踝肱指数=踝部最高收缩压/肱动脉最高收缩压；取双腿较低指数

## 已记录的公式

每条腿的踝肱指数=该踝部最高收缩压÷双臂中最高肱动脉收缩压。患者的踝肱指数取两侧较低值。

## 限制与适用人群

每条腿应使用该侧踝部最高收缩压除以双臂中最高收缩压，不要取这些压力的平均值。糖尿病和慢性肾病中常见的不可压缩动脉可能使指数假性升高，需进一步评估。静息正常值不能排除所有缺血，单独指数在慢性肢体威胁性缺血中可能不足。工具不能代替正确测量技术、症状、血管检查或补充检验。

## 参考文献

- [Aboyans V et al. Measurement and interpretation of the ankle-brachial index: a scientific statement from the American Heart Association. Circulation, 2012.](https://doi.org/10.1161/CIR.0b013e318276fbcb)

- [Gerhard-Herman MD et al. 2016 AHA/ACC Guideline on the Management of Patients With Lower Extremity Peripheral Artery Disease. Circulation, 2017.](https://doi.org/10.1161/CIR.0000000000000471)

- [AHA/ACC2024 lower-extremity PAD guideline](https://www.ahajournals.org/doi/full/10.1161/CIR.0000000000001251)

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

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

分类：轻度 PAD

| 结果详情 | |
| --- | --- |
| 右侧 ABI | 0.90（轻度 PAD） |
| 左侧 ABI | 1.08（正常） |
| 所用肱动脉压 | 130 mmHg |


### 2

至少一侧动脉不可压缩：使用趾臂指数

| 结果详情 | |
| --- | --- |
| 右侧 ABI | 1.50（不可压缩） |
| 左侧 ABI | 1.08（正常） |
| 所用肱动脉压 | 120 mmHg |

