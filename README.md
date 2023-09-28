# Audit of web-crawled multilingual corpora

This repository contains the results of the manual audit of web-crawled multilingual corpora for language varieties of Italy. Motivation, methodology, results, and insights for this study are described in:

Alan Ramponi. 2023. **Language Varieties of Italy: Technology Challenges and Opportunities**. (to appear) [[cite]](#citation) [[preprint]](https://arxiv.org/abs/2209.09757)


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
@article{ramponi-2022-language,
	title={{NLP} for language varieties of {I}taly: Challenges and the path forward},
	author={Ramponi, Alan},
	journal={arXiv preprint arXiv:2209.09757},
	year={2022},
	url={https://arxiv.org/abs/2209.09757}
}
```