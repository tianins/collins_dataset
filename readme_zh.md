# Collins-WSD Dataset (v1.0)
`Improved Word Sense Disambiguation via Prompt-based Contextual Word Representation` 论文配套数据集

## 中文说明

### 数据集概述
本数据集包含从[柯林斯词典](https://www.collinsdictionary.com/dictionary/english)爬取的**54,709个词义消歧标注例句**，用于英语词汇多义词消歧任务。数据按8:1:1比例划分为：
- 训练集：43717句
- 测试集：5498句 
- 开发集：5494句

### 数据格式
Excel文件包含以下列：

| 列名            | 描述                                                                 |
|-----------------|----------------------------------------------------------------------|
| Word            | 需要消歧的单词原形（如：long）                                       |
| POS             | 词性标注（如：adv）                                                  |
| Sense ID        | 词义编号（格式：`<word>!@!<pos>!@!<num>`，例：long!@!adv!@!0）              |
| Sentence        | 包含目标词的完整例句                                                 |
| Target Word     | 例句中实际出现的词形（可能与Word不同，如复数/时态变化）              |
| Sense Definition| 该语境下的词义解释（来自柯林斯词典）                                 |

### 引用格式
若使用本数据集，请引用原始论文：
```bibtex
@INPROCEEDINGS{10191929,
  author    = {He, Qipeng and Zhang, Jian and Huang, Xueting},
  title     = {Improved Word Sense Disambiguation via Prompt-based Contextual Word Representation}, 
  booktitle = {2023 International Joint Conference on Neural Networks (IJCNN)},
  year      = {2023},
  pages     = {1-8},
  doi       = {10.1109/IJCNN54540.2023.10191929}
}
```


### 注意事项

1. 数据仅限研究使用
2. 原始词典内容版权归Collins Publishers所有
3. 请遵守[原始网站](https://www.collinsdictionary.com/)的使用条款
