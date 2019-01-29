# English-Gujarati TQE Dataset (news.gu)

If you use this dataset for research, cite at least one or both of the following papers depending on context. In any other context, give appropriate attribution.

[1] Nisarg Jhaveri, Manish Gupta, and Vasudeva Varma. 2018. A Workbench for Rapid Generation of Cross-Lingual Summaries. In *Proceedings of the Eleventh International Conference on Language Resources and Evaluation (LREC-2018)*.

[2] Nisarg Jhaveri, Manish Gupta, and Vasudeva Varma. 2018. Translation Quality Estimation for Indian Languages. In *Proceedings of the 21st Annual Conference of the European Association for Machine Translation (EAMT)*.

---

This repository contains dataset prepared by and described by the two papers listed above.

### `raw_data/`
This directory contains unprocessed and semi-processed dataset created using the workbench described by [1].

The `*.dump` files in the directory are the raw data dump of the data generated in JSON format.

The two sub-directories, `manually_translated` and `post_edited` contains some processed data derived from the dump files.

`manually_translated` data contains 112 articles, manually translated to Gujarati from English.

`post_edited` data contains 395 articles, which were translated using Google Translate and post-edited.

See the paper [1] for more details.

### `tqe/`
This  directory contains prepared dataset that was used for Translation Quality Estimation in [2]. This dataset is referenced as `news.gu` in the paper.

The data contains 5612 sentences from the 395 post-edited articles. See the paper [2] for more details.

---

#### BibTeX entries
```
@inproceedings{jhaveri2018workbench,
  title={A Workbench for Rapid Generation of Cross-Lingual Summaries},
  author={Jhaveri, Nisarg and Gupta, Manish and Varma, Vasudeva},
  booktitle={Proceedings of the Eleventh International Conference on Language Resources and Evaluation (LREC-2018)},
  year={2018},
  isbn = {979-10-95546-00-9},
}

@inproceedings{jhaveri2018qe,
  title = {Translation Quality Estimation for Indian Languages},
  author = {Nisarg Jhaveri and Manish Gupta and Vasudeva Varma},
  booktitle = {Proceedings of the 21st Annual Conference of the European Association for Machine Translation (EAMT)},
  year = {2018},
  isbn = {978-84-09-01901-4},
}
```

---

This dataset is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

This license applies to all derivative or original works, which does not include the source articles used to prepare the dataset. The source articles are licensed by their respective owners.
