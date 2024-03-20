# 3AM: An Ambiguity-Aware Multi-Modal Machine Translation Dataset

We introduce 3AM: an ambiguity-aware multimodal machine translation dataset with ~26K image-text pairs for multimodal machine translation. Compared with previous MMT datasets, our dataset encompasses a greater diversity of caption styles and a wider range of visual concepts. Please check out our paper for more details.

## Download

Please download the dataset at [here](https://drive.google.com/drive/folders/1q_TS76NUB9WpBVf9eblMFnEytdFAQVRt?usp=drive_link). The text data is also available at the `data` folder.

## Training

### Selective Attention

The code for training the selective attention model is available [here](https://github.com/MaxyLee/fairseq_mmt), which is base on [fairseq-mmt](https://github.com/libeineu/fairseq_mmt).

```
# train
bash train_mmt.sh
# test
bash translate_mmt.sh
```

### VL-Bart, VL-T5

The code for training the VL-Bart and VL-T5 model is available [here](https://github.com/MaxyLee/VL-T5), which is based on [VL-T5](https://github.com/j-min/VL-T5).

```
# VL-Bart
bash scripts/MMT_VLBart.sh
# VL-T5
bash scripts/MMT_VLT5.sh
```

## Contact

If you have any questions, please email yc27434@umac.mo.

## Citation

If you use this dataset in your research, please cite:

```
TODO
```
