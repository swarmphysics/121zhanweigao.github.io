---
layout: post
title:  "About the project: Genre Classification for shorter texts"
date:   2021-12-02 23:10:00
blurb: "About the project"
og_image: /assets/img/content/post-example/Banner.jpg
---
<br />
#### Table of Contents
1. [About](#about)
  * [Our Contributions](#our-contributions)
2. [Links](#links)

#### About

**Guide** - Dr. Kushal Shah, IISER Bhopal (Indian Institute of Science Education and Research)

**Team Members** - Atmaja Jape, CCEW

##### Our Contributions

Initially, we worked on extending the work done in [this paper](https://aclanthology.org/W19-3409.pdf) for book summaries found in the CMU Book Summary Dataset. The direction of our research was adapted after the results obtained through this activity. We found that book summaries were harder to classify on the basis of their genres. In order to investigate the cause behind the same, we carried out further analysis on the Brown Corpus.

The purpose of the Brown Corpus Analysis was to explore two directions - effect of document size of genre classification, and effect of stylistic tendencies for text generation on genre classification.

As part of this project, I gained knowledge into feature Investigation, including Part-of-Speech tagging. We used two taggers, namely Stanford Tagger and NLTK Tagger. It was also interesting for us to observe the differences in tagging by both the taggers for the same corpus.

We also performed visualisation for the features of text. One interesting visualisation was the 3D representation of the features divided by their genres.

As part of the methodology, we derived a unique Genre Category Score from the results of clustering to observe the distinction in genres of text based on the features of the text under consideration. Our cimple linguistic approach for genre classification for short text documents performed significantly well on the Brown Corpus. We implemented the strategy on documents of varying sizes, from 150 - 600 words.

By using the strategy on the CMU Corpus, we were also able to determine the stylistic choices for book summary generation in contrast with the choices for text document generation.

We experimented with several classification models, including Support Vector Machines and Bagging Classifier, and clustering models, including K-Means and Gaussian Mixture Model.

Being a literature enthusiast, this project was very interesting for me and I hope to further continue working in this domain.

#### links

1. [Brown Corpus](https://www.kaggle.com/nltkdata/brown-corpus)
2. [CMU Corpus](https://www.cs.cmu.edu/~dbamman/booksummaries.html)
3. [Stanford Tagger](https://nlp.stanford.edu/software/tagger.shtml)
