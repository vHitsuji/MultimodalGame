# MultimodalGame

This is a framework for studying multi-agent emergent communication It enables a user to investigate the cultural and communicative aspects of a linguistic community of trainable agents based on deep learning and reinforcement learning

## Installation

```bash
git clone --recurse-submodules https://github.com/lgraesser/MultimodalGame.git
cd MultimodalGame
pip install -e ShapeWorld
```

## Dependencies

# TODO update

You can install the dependencies using pip: `pip install -r requirements.txt` or install them manually.

## Building the Datasets

This model used ShapeWorld datasets. All the datasets used in this project are available [here](**TODO**)

To generate an example dataset run the following command. This generates 5000 examples and is equivalent to the training dataset "oneshape" used for this project, available [here](**TODO**).

```
mkdir data
cd ShapeWorld
./build_datasets.sh
cd ..
```

The models also depends on pretrained word embeddings. We recommend using the `6B.100d` GloVe embeddings available [here](https://nlp.stanford.edu/projects/glove/).

### About ShapeWorld

ShapeWorld is a framework which allows to specify generators for abstract, visually grounded language data (or just visual data).

It was written by *Alexander Kuhnle and Ann Copestake* (April 2017) and adapted by Laura Graesser for this project.

If you use ShapeWorld in your work, please cite:

> **ShapeWorld: A new test methodology for multimodal language understanding** ([arXiv](https://arxiv.org/abs/1704.04517))
> *Alexander Kuhnle and Ann Copestake* (April 2017)

For more details, please see the [original repository](https://github.com/AlexKuhnle/ShapeWorld)

### Example Data

**Images**

**Partitioned Images**
(Partitions randomly generated at run time)

*Partition 1*

*Partition 2*

**Correct Description**

**Texts**

## Training agents

### Basic case

### Agent Pools

### Agent Communities

## Generating messages

## Evaluating agents

### Accuracy

### Protocol similarity
