### Dataset Overview

This dataset contains **54,709 sense-annotated sentences** crawled from [Collins Dictionary](https://www.collinsdictionary.com/dictionary/english) for English Word Sense Disambiguation (WSD). Split ratio:

- Training Set: 43717 sentences
- Test Set: 5498 sentences
- Development Set: 5494 sentences

### Data Format

Excel files include the following columns:

| Column           | Description                                                               |
| ---------------- | ------------------------------------------------------------------------- |
| Word             | Target lemma (e.g., long)                                                 |
| POS              | Part-of-speech tag (e.g., adv)                                            |
| Sense ID         | Sense identifier (format: `<word>!@!<pos>!@!<num>`, e.g., long!@!adv!@!0) |
| Sentence         | Full context sentence                                                     |
| Target Word      | Surface form in sentence (may differ from lemma)                          |
| Sense Definition | Sense definition from Collins Dictionary                                  |


### Citation

Please cite the original paper if using this dataset:

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

### Notes

1. For research purposes only
2. Dictionary content © Collins Publishers
3. Comply with [source website terms](https://www.collinsdictionary.com/)
