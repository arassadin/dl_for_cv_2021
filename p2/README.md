# Week #2. Image Classification

## Files description.

### `p2.ipynb`

This is `colab`-ready notebook containing the practical lessons code. Store it somewhere on your Google Drive to run without modifications via the [Google Colab](https://colab.research.google.com/) or modify correspondingly to run via the [Jupyter](https://jupyter.org/).

Please refer to the corresponding lecture for the usage details.

### `grouping.py`, `interpparts.py`

These files are required for the full notebook execution. They contains the code from the section `Interp-Parts` in the notebook and necessary for the model initialization and usage. These files are freezed from the [original repo](https://github.com/zxhuang1698/interpretability-by-parts), specifically from [here](https://github.com/zxhuang1698/interpretability-by-parts/blob/2ec9302b9961bf3beba1ae8a12dd3ad1570bf674/src/common/grouping.py) and [here](https://github.com/zxhuang1698/interpretability-by-parts/blob/2ec9302b9961bf3beba1ae8a12dd3ad1570bf674/src/cub200/model.py). Our thanks to authors for their work.

Store these files in the same folder with the notebook.

## Refferences

```
@techreport{WahCUB_200_2011,
Title = {{The Caltech-UCSD Birds-200-2011 Dataset}},
Author = {Wah, C. and Branson, S. and Welinder, P. and Perona, P. and Belongie, S.},
Year = {2011}
Institution = {California Institute of Technology},
Number = {CNS-TR-2011-001}
}
```
```
@InProceedings{Huang_2020_CVPR,
author = {Huang, Zixuan and Li, Yin},
title = {Interpretable and Accurate Fine-grained Recognition via Region Grouping},
booktitle = {The IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2020}
}
```