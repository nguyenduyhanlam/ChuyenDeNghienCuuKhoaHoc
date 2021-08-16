# Transformer-Alignment
This page includes instructions for training models described in  [Accurate Word Alignment Induction from Neural Machine Translation (Chen et al., 2020)](https://www.aclweb.org/anthology/2020.emnlp-main.42/)

First install fairseq-v0.9.0 with guidance [here](https://github.com/pytorch/fairseq/tree/v0.9.0). Then process data with the [guidance](https://github.com/lilt/alignment-scripts/tree/master/preprocess) and get binarized processed data with `fairseq-preprocess` command.

More details are in scripts/run.sh file.