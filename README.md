# Audit of web-crawled multilingual corpora

This repository contains the results of the manual audit of web-crawled multilingual corpora for language varieties of Italy. Motivation, methodology, results, and insights for this study are described in:

Alan Ramponi. 2024. **Language Varieties of Italy: Technology Challenges and Opportunities**. *Transactions of the Association for Computational Linguistics*, 12, 19–38. DOI: doi.org/10.1162/tacl_a_00631 [[cite]](#citation) [[paper]](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00631/119058/Language-Varieties-of-Italy-Technology-Challenges)


### Repository structure

The repository includes folders denoting audited language portions (ISO 639-3 codes) of web-crawled multilingual corpora. Each folder contains tab-separated files (`.tsv`) for audited material for the language portion (the column `classification` indicates the annotation for each row, and `notes` the additional observations):

- `lmo`: manual audit for the `lmo` portion on OSCAR v22.01;
- `pms`: manual audit for the `pms` portion on OSCAR v22.01;
- `scn`: manual audit for the `scn` portion on OSCAR v22.01 and WikiMatrix (i.e., parallel subset `it-scn`);
- `srd`: manual audit for the `srd` portion on CCAligned (i.e., parallel subset `en-sc`).

*Note that the `en-lmo` parallel subset of WikiMatrix has already been audited in [Kreutzer et al. (2022)](https://aclanthology.org/2022.tacl-1.4/).*

The corpora have been originally introduced in [Abadji et al. (2022)](https://aclanthology.org/2022.lrec-1.463/) (OSCAR v22.01), [Schwenk et al. (2021)](https://aclanthology.org/2021.eacl-main.115/) (WikiMatrix), and [El-Kishky et al. (2020)](https://aclanthology.org/2020.emnlp-main.480/) (CCAligned).


### Citation

If you find this study useful for your work or you use the results, please cite our paper as follows:

```
@article{ramponi-2024-language,
    author = {Ramponi, Alan},
    title = "{Language Varieties of Italy: Technology Challenges and Opportunities}",
    journal = {Transactions of the Association for Computational Linguistics},
    volume = {12},
    pages = {19-38},
    year = {2024},
    month = {01},
    issn = {2307-387X},
    doi = {10.1162/tacl_a_00631},
    url = {https://doi.org/10.1162/tacl\_a\_00631},
    eprint = {https://direct.mit.edu/tacl/article-pdf/doi/10.1162/tacl\_a\_00631/2208870/tacl\_a\_00631.pdf},
}
```