this repository contains bunch of experiences on [MedNli dataset](https://paperswithcode.com/dataset/mednli).
remember to upload the dataset files (in parquet format) before running the notebooks.

# Sci5
[SciFive](https://github.com/justinphan3110/SciFive) is the state of the art for medical language inference, this language model achieved 86% accuracy on MedNli dataset.
you can use [this notebook](https://github.com/Mehrdadghassabi/Mednli_experiments/blob/main/Sci5/Untitled63.ipynb) to evaluate its performance

# Simple feed forward
for textual inference the most simple thing that comes to mind is to extract premise and hypothesis word embedding concatenating them and within a simple feed forward layer do the classification task.
it can achieve about 68% accuracy on MedNli dataset.
see [this notebook](https://github.com/Mehrdadghassabi/Mednli_experiments/blob/main/Simple_feed_forward/Notebooks/Untitled59.ipynb) for further informations.

# Recurrent neural networks
