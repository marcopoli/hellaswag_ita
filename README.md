# Italian version of the HellaSwag Dataset
The dataset has been automatically translate by using [Argos Translate](https://github.com/argosopentech/argos-translate) v. 1.9.1

### Citation Information

```
@misc{basile2023llamantino,
      title={LLaMAntino: LLaMA 2 Models for Effective Text Generation in Italian Language}, 
      author={Pierpaolo Basile and Elio Musacchio and Marco Polignano and Lucia Siciliani and Giuseppe Fiameni and Giovanni Semeraro},
      year={2023},
      eprint={2312.09993},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}

@inproceedings{zellers2019hellaswag,
    title={HellaSwag: Can a Machine Really Finish Your Sentence?},
    author={Zellers, Rowan and Holtzman, Ari and Bisk, Yonatan and Farhadi, Ali and Choi, Yejin},
    booktitle ={Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics},
    year={2019}
}

```

<br>
<br>
</hr>

# Original English version of the "hellaswag" dataset

## Table of Contents
- [Dataset Description](#dataset-description)
  - [Dataset Summary](#dataset-summary)
  - [Languages](#languages)
- [Dataset Structure](#dataset-structure)
  - [Data Instances](#data-instances)
  - [Data Fields](#data-fields)
  - [Data Splits](#data-splits)
- [Additional Information](#additional-information)
  - [Licensing Information](#licensing-information)

## Dataset Description

- **Homepage:** [https://rowanzellers.com/hellaswag/](https://rowanzellers.com/hellaswag/)
- **Repository:** [https://github.com/rowanz/hellaswag/](https://github.com/rowanz/hellaswag/)
- **Paper:** [HellaSwag: Can a Machine Really Finish Your Sentence?](https://arxiv.org/abs/1905.07830)
- **Size of downloaded dataset files:** 71.49 MB
- **Size of the generated dataset:** 65.32 MB
- **Total amount of disk used:** 136.81 MB

### Dataset Summary

HellaSwag: Can a Machine Really Finish Your Sentence? is a new dataset for commonsense NLI. A paper was published at ACL2019.


### Languages
EN - ITA

## Dataset Structure

### Data Instances

#### default

- **Size of downloaded dataset files:** 71.49 MB
- **Size of the generated dataset:** 65.32 MB
- **Total amount of disk used:** 136.81 MB

An example of 'train' looks as follows.
```
This example was too long and was cropped:

{
    "activity_label": "Removing ice from car",
    "ctx": "Then, the man writes over the snow covering the window of a car, and a woman wearing winter clothes smiles. then",
    "ctx_a": "Then, the man writes over the snow covering the window of a car, and a woman wearing winter clothes smiles.",
    "ctx_b": "then",
    "endings": "[\", the man adds wax to the windshield and cuts it.\", \", a person board a ski lift, while two men supporting the head of the per...",
    "ind": 4,
    "label": "3",
    "source_id": "activitynet~v_-1IBHYS3L-Y",
    "split": "train",
    "split_type": "indomain"
}
```

### Data Fields

The data fields are the same among all splits.

#### default
- `ind`: a `int32` feature.
- `activity_label`: a `string` feature.
- `ctx_a`: a `string` feature.
- `ctx_b`: a `string` feature.
- `ctx`: a `string` feature.
- `endings`: a `list` of `string` features.
- `source_id`: a `string` feature.
- `split`: a `string` feature.
- `split_type`: a `string` feature.
- `label`: a `string` feature.

### Data Splits

| name  |train|validation|test |
|-------|----:|---------:|----:|
|default|39905|     10042|10003|


### Licensing Information

MIT https://github.com/rowanz/hellaswag/blob/master/LICENSE




### Contributions

Thanks to [@albertvillanova](https://github.com/albertvillanova), [@mariamabarham](https://github.com/mariamabarham), [@thomwolf](https://github.com/thomwolf), [@patrickvonplaten](https://github.com/patrickvonplaten), [@lewtun](https://github.com/lewtun) for adding this dataset.
