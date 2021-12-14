# A Simple and Effective Method To Eliminate the Self Language Bias in Multilingual Representations (LIR)

The official implementations for the EMNLP 2021 paper
[A Simple and Effective Method To Eliminate the Self Language Bias in Multilingual Representations](https://arxiv.org/abs/2109.04727).

[__Ziyi Yang__](https://web.stanford.edu/~zy99/), __Yinfei Yang__, __Daniel Cer__, __Eric Darve__

-------------------------------------------------------------------------------------
Language agnostic and semantic-language information isolation is an emerging research direction for multilingual representations models. We explore this problem from a novel angle of geometric algebra and semantic space. A simple but highly effective method "Language Information Removal (LIR)" factors out language identity information from semantic related components in multilingual representations pre-trained on multi-monolingual data. A post-training and model-agnostic method, LIR only uses simple linear operations, e.g. matrix factorization and orthogonal projection. LIR reveals that for weak-alignment multilingual systems, the principal components of semantic spaces primarily encodes language identity information. We first evaluate the LIR on a cross-lingual question answer retrieval task (LAReQA), which requires the strong alignment for the multilingual embedding space. Experiment shows that LIR is highly effectively on this task, yielding almost 100% relative improvement in MAP for weak-alignment models. We then evaluate the LIR on Amazon Reviews and XEVAL dataset, with the observation that removing language information is able to improve the cross-lingual transfer performance.

## Dataset
LIR tests on [LAReQA](https://arxiv.org/abs/2004.05484) dataset. The folder xquad-r is directly copied from LAReQA official [repo](https://github.com/google-research-datasets/lareqa). Dataset mlqa-r can be found [here](https://github.com/google-research-datasets/lareqa/tree/354d67d1cd066854cdfbf5ad0e6105528976141d).

## Cite LIR
If you find LIR useful for you research, please cite our paper:
```bib
@inproceedings{yang-etal-2021-simple,
    title = "A Simple and Effective Method To Eliminate the Self Language Bias in Multilingual Representations",
    author = "Yang, Ziyi  and
      Yang, Yinfei  and
      Cer, Daniel  and
      Darve, Eric",
    booktitle = "Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2021",
    address = "Online and Punta Cana, Dominican Republic",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.emnlp-main.470",
    pages = "5825--5832",
}
```
