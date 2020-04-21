# Automatic Post-Editing (APE) Dataset with operation order

If you use this dataset, please cite the following:
```
@inproceedings{gois-cho-martins-2020-non-monotonic-ape,
    title = "Learning Non-Monotonic Automatic Post-Editing of Translations from Human Orderings",
    author = "G{\'o}is, Ant{\'o}nio  and
      Cho, Kyunghyun and
      Martins, Andr{\'e} F. T.",
    year = "2020",
    publisher = "European Association for Machine Translation",
}
```

The dataset presented here is a subset of the training sets provided by [WMT-APE shared](http://www.statmt.org/wmt18/ape-task.html) tasks of 2016 and 2017:
- Language pair: English to German
- Phrase-Based Statistical Machine Translation System
- Domain: Information Technology

Out of the 23,000 samples provided by WMT, we present 16,068 which are also found in the dataset introduced by [Specia et al. (2017)](https://cris.fbk.eu/retrieve/handle/11582/313118/21555/specia_et_al_2017_translation_quality_and_productivity.pdf). By intersecting both datasets, we obtain the raw keylogs of the editors correcting the original Machine-Translation output. After preprocessing the keylogs, we obtain sequences of token-level INSERT and DELETE operations.

