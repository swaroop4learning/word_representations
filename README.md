# Word Representations
NLP encompasses various tasks - Regression, Classification, Generation. A common
denominator across all these tasks is the question of "how do we convert text into
numbers" so that machines can process them. One way to measure a machine's ability
to “understand” text is Semantic Similarity i.e one should be able to tell you how similar
or dissimilar are a given pair of inputs - and this is the central theme of this task

## About
This repository consists of two parts:<br>
<b>1st part</b>: Possible solutions for word representation tasks. Which would create efficient word representations that would help in performing word similarity, paraphrase and sentence similarities. <br>
<b>2nd part</b>: Paper reading task, where the metric BERTScore is evaluated with pros and cons. And also provided possible improvements for BERTScore metric.

## Project Files
task_notebooks_src: This module has the standalone jupyter notebooks for performing various word representation tasks
word_similarity_task_constrained.ipynb: This notebook has code to create word representations on constrained sources. That has SVD implementation.
word_similarity_unconstrained.ipynb: This notebook has code to create word representations on unconstrained. Hence the word representations have semantics learned.
phrase_similarity_task.ipynb: This notebook has implementation to load word2vec static embeddings and then train various supervised models for phrase detection.
sentence_similarity_task.ipynb: This notebook has siamese bilstm network for sentence similarity. It also has bonus task of finetuning the transformer based model for sentence similarity task.
BERTScore.pdf: This has the paper reading task that evaluates the BertScore metric by referring to this paper: https://arxiv.org/pdf/1904.09675.pdf

## Dependencies
### Datasets for the tasks can be downloaded from here and placed in the task_notebook_src folder
https://fh295.github.io/SimLex-999.zip
https://huggingface.co/datasets/PiC/phrase_similarity
https://huggingface.co/datasets/paws

### Requirements
Install the dependencies from requirements.txt with pip install -r requirements.txt

#### Contact author for any queries to reproduce the results
