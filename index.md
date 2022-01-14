---
layout: default
---
This website hosts the upcoming tutorial series for advanced NLP methods, for computational social science scholars.

Every few weeks, we will host some experts in the field of computational social science to present a new method in NLP, and to lead participants in an interactive exploration of the method with code and sample text data.
If you are a graduate student or researcher who has some introductory knowledge of NLP (e.g. has learned text analysis from [SICSS](https://sicss.io/curriculum)) and wants to "level up", come join us!

Watch past tutorials on [our YouTube channel](https://www.youtube.com/channel/UCcFcF9DkanjaK3HEk7bsd-A). 

## Tutorial format

- **Introduction**: the facilitators introduce their method and the code/data associated with the method.
- **Interaction**: the participants break out into small groups to test out the method using the provided code. The code includes several spots for experimenting with the method, which can help the participants better understand the benefits and limitations of the method. The participants may also bring their own data for analysis if desired.
- **Conclusion**: the facilitators bring all participants together to collect their experiences with the method and to share final thoughts on possible improvements on the method.

Tutorials will last one hour and we encourage participants to join live. However, we will also make the recordings and code publicly available afterwards.


## Logistics on joining tutorials live   

We will send out the tutorial video link to our mailing list a few days before the tutorial starts.
If you want to join the mailing list, subscribe [here](https://groups.google.com/g/nlp-css-tutorials).

## Schedule

- February-May 2022: topics include dialogue, phrase extraction, analytical uncertainty, causal inference, multilingual NLP, social media preprocessing.

## Archive

See below for links to materials for previous tutorials.

| Tutorial| Description| Leader| Code| Video| Slides|
|---|---|---|---|---|---|
| Comparing Word Embedding Models| We'll demonstrate an extension of the use of word embedding models by fitting multiple models on a social science corpus (using gensim's word2vec implementation), then aligning and comparing those models. This method is used to explore group variation and temporal change. We'll discuss some tradeoffs and possible extensions of this approach.| [Connor Gilroy](https://ccgilroy.com/), [Sandeep Soni](https://sandeepsoni.github.io/) | [link](https://colab.research.google.com/drive/16cM5NXedlrvU2mp-HcYKs9OIMkYItTS1?usp=sharing) | [link](https://youtu.be/WbzPZZKJRJA)| N/A|
| Extracting Information from Documents| This workshop provides an introduction to information extraction for social science–techniques for identifying specific words, phrases, or pieces of information contained within documents. It focuses on two common techniques, named entity recognition and dependency parses, and shows how they can provide useful descriptive data about the civil war in Syria. The workshop uses the Python library spaCy, but no previous experience is needed beyond familiarity with Python.| [Andrew Halterman](https://www.andrewhalterman.com/)| [link](https://colab.research.google.com/drive/1U6x-3OVCGtx9CBZvzdJi8mhTxCx8k4Ie?usp=sharing) | [link](https://youtu.be/sUtthdcPyhc)| N/A|
| Controlling for Text in Causal Inference with Double Machine Learning| Establishing causal relationships is a fundamental goal of scientific research. Text plays an increasingly important role in the study of causal relationships across domains especially for observational (non-experimental) data. Specifically, text can serve as a valuable "control" to eliminate the effects of variables that threaten the validity of the causal inference process. But how does one control for text, an unstructured and nebulous quantity? In this tutorial, we will learn about bias from confounding, motivation for using text as a proxy for confounders, apply a "double machine learning" framework that uses text to remove confounding bias, and compare this framework with non-causal text dimensionality reduction alternatives such as topic modeling. | [Emaad Manzoor](https://emaadmanzoor.com/)| [link](https://colab.research.google.com/drive/15Jz9QehJsT2um1cH5GEbbBOeJDcX0e2n?usp=sharing) | [link](https://youtu.be/DwUqA1ydJI0)| [link](docs/NLP+CSS201 - Controlling for Text in Causal Inference.pdf)|
| Beyond the Bag Of Words: Text Analysis with Contextualized Topic Models | Most topic models still use Bag-Of-Words (BoW) document representations as input. These representations, though, disregard the syntactic and semantic relationships among the words in a document, the two main linguistic avenues to coherent text. Recently, pre-trained contextualized embeddings have enabled exciting new results in several NLP tasks, mapping a sentence to a vector representation. Contextualized Topic Models (CTM) combine contextualized embeddings with neural topic models to increase the quality of the topics. Moreover, using multilingual embeddings allows the model to learn topics in one language and predict them for documents in unseen languages, thus addressing a task of zero-shot cross-lingual topic modeling.|  [Silvia Terragni](https://silviatti.github.io/)| [link](https://colab.research.google.com/drive/1EO0bS0Wow_cjdGsDfV38xt--AxJQjFtg?usp=sharing) | [link](https://www.youtube.com/watch?v=n1_G8K07KoM) | N/A|
| BERT for Computational Social Scientists| What is BERT? How do you use it? What kinds of computational social science projects would BERT be most useful for? Join for a conceptual overview of this popular natural language processing (NLP) model as well as a hands-on, code-based tutorial that demonstrates how to train and fine-tune a BERT model using HuggingFace's popular Python library.| [Maria Antoniak](https://maria-antoniak.github.io/)| [link](https://colab.research.google.com/drive/1ih6ETBCU2Dqr1_aTPgjS_Ww3xXVswIO0?usp=sharing) | [link](https://youtu.be/UmyOhl9AciI)| [link](https://docs.google.com/presentation/d/1HGWnLkv7_2fST9tFVbvQbY-rN4aTMjJW/) |

## Hosts

This tutorial series is organized by:

<img src="https://ianbstewart.github.io/docs/istewart.jpg" alt="ian_pic" width="200"/>
- [Ian Stewart](https://ianbstewart.github.io): post-doctoral fellow at University of Michigan; researches personalization and writing interventions for social applications

<img src="https://kakeith.github.io/images/kk.jpg" alt="katie_pic" width="200"/>
- [Katie Keith](https://kakeith.github.io/): post-doctoral researcher at AI2 and incoming Assistant Professor at Williams College (Fall 2022); researches causal inference with text and text-based social data science. 


## Acknowledgments 
We are deeply grateful for financial assistance from a [Social Science Research Council (SSRC)](https://www.ssrc.org/)/[Summer Institutes in Computational Social Science (SICSS)](https://sicss.io/) Research Grant.

### Theme

TBD
