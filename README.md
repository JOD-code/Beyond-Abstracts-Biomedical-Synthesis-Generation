# Beyond-Abstracts-Biomedical-Synthesis-Generation

This repository stores the dataset for our paper [Beyond Abstracts: A New Dataset, Prompt Design Strategy and Method for Biomedical Synthesis Generation](https://aclanthology.org/2024.acl-srw.42/). The dataset is a nested Pandas dataframe saved in pickle format.

## Contact
If you have any questions you can contact us at james.odoherty3@mail.dcu.ie or cian.nolan95@mail.dcu.ie.

## Citation
If you find our work helpful, please leave us a star and cite our paper.

```
@inproceedings{odoherty-etal-2024-beyond,
    title = "Beyond Abstracts: A New Dataset, Prompt Design Strategy and Method for Biomedical Synthesis Generation",
    author = "O{'}Doherty, James  and
      Nolan, Cian  and
      Hou, Yufang  and
      Belz, Anya",
    editor = "Fu, Xiyan  and
      Fleisig, Eve",
    booktitle = "Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 4: Student Research Workshop)",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.acl-srw.42",
    pages = "499--518",
    abstract = "The biomedical field relies on cost and time intensive systematic reviews of papers to enable practitioners to keep up to date with research. Impressive recent advances in large language models (LLMs) have made the task of automating at least part of the systematic review process feasible, but progress is slow. This paper identifies some factors that may have been holding research back, and proposes a new, enhanced dataset and prompting-based method for automatic synthesis generation, the most challenging step for automation. We test different models and types of information from and about biomedical studies for their usefulness in obtaining high-quality results.We find that, surprisingly, inclusion of paper abstracts can worsens results. Instead, study summary information, and system instructions informed by domain knowledge, are key to producing high-quality syntheses.",
}

```