# ML-Portfolio
This repo contain some of my projects, including using Spark for big data analysis, fine tuning GPT-2, question answering using T5, full page handwriting recognetion using vision transformers(Vit, Swin, ... ) and large language models(Bart, GPT, ..)


## Spark Higges Analysis

The notebook provides using multilayer perceptron for analayzing Higgs Dataset via Spark. The notebook could be executed on IBM Watson. 
Higgs dataset is used as a benchmark to test Machine Learning algorithms performance on the task of identifying nuclear collisions that produce the HIGGS boson versus background process.

The data set consists of 11 Million Monte Carlo simulations of nuclear collisions. Signal collisions correspond to collisions where a Higgs boson was created. Background collisions correspond to collisions that have the same end product particles but where a Higgs boson was not created. Each collision has 28 attributes. 

We have used startified Sampling for create groups of data and reduce computation time.

Data set location: [https://archive.ics.uci.edu/ml/datasets/HIGGS]


Relevant Paper: Baldi, P., P. Sadowski, and D. Whiteson. “Searching for Exotic Particles in High-energy Physics with Deep Learning.” Nature Communications 5 (July 2, 2014)

## Donut Paper

Minimal Implementation of **Donut** 🍩, **Do**cume**n**t **u**nderstanding **t**ransformer, is a new method of document understanding that utilizes an OCR-free end-to-end Transformer model. Donut does not require off-the-shelf OCR engines/APIs, yet it shows state-of-the-art performances on various visual document understanding tasks, such as visual document classification or information extraction (a.k.a. document parsing). <br>
> [**OCR-free Document Understanding Transformer**](https://arxiv.org/abs/2111.15664).<br>


## Question Answering Using T5

Using T5 for persian question answering fine tuned on Persian-SQUAD, see the dtaset here: https://github.com/sajjjadayobi/PersianQA/tree/main/dataset

## Fine Tune GPT-2

Using Hugging Face Transformers for fine tuning gpt-2 on diffrent datasets, in my case a bunch of quantum mechanic books.
