# text-entailment-elmo


### Task Description:

We are attempting the problem of **Text Entailment**, which is determining whether a piece of text logically follows from another piece of text. It is the task of **Natural Language Inference (NLI)** where given pairs of small text snippets (one or more sentences in English), known as Text-Hypothesis (T-H) pairs, we have to decide if the **hypothesis contradicts, entails or is neutral to the text.** 

In this project , we are performing a quantitative analysis of prevalent models and embeddings and we are evaluating which architecture is the best for the text entailment task. 

### Description about the Dataset:

For our task, we have used the Stanford Natural Language Inference (SNLI) corpus, which is a collection of 570k human-written English sentence pairs manually labeled for balanced classification with the labels entailment, contradiction, and neutral. Each entry in the dataset is a pair of hypothesis and baseline with gold-label, and the parse structure of sentences in Penn Treebank format. There are 550152 training pairs, 10000 validation and 10000 test pairs.

This complete dataset for the task can be downloaded from [this website](https://nlp.stanford.edu/projects/snli/). 



### Code Files:

* `elmo-embedding-all-models.ipynb` : All models (CNN + LSTM + Bi-LSTM) built on ELMo Embeddings.

### References:

1. https://github.com/DamianValle/deep-entailment
2. https://github.com/PatrickBD/Natural_Language_Processing_Compilation
