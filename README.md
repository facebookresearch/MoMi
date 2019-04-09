# MoMi (Model Mistakes) Dataset

Dataset for [Generate, Filter, and Rank: Grammaticality Classification for Production-Ready NLG Systems](https://arxiv.org/abs/1904.03279). These are responses produced by our NLG model, tagged for grammaticality and correctness by annotators.

## Dataset columns

- grammatical: whether text is grammatical (1) or not (0)
- correct: whether the response correctly expresses information provided in goal and scenario (1) or not (0)
- text: response produced by model
- tag: source of text
- goal: intent to be expressed in text
- scenario: input to model which produced the text

## Citation
```
@inproceedings{Challah:2019,
  author={Challa, Ashwini and  Upasani, Kartikeya and Balakrishnan, Anusha and Subba, Rajen},
  title={Generate, Filter, and Rank: Grammaticality Classification for Production-Ready NLG Systems},
  booktitle={Proc. of NAACL Industry Track},
  year={2019}
}
```

## License
MoMi is Creative Commons Attribution-NonCommercial 4.0 International Public licensed, as found in the LICENSE file.
