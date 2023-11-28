---
title: Natural Language Processing

# View.
#   1 = List
#   2 = Compact
#   3 = Card
view: 2

# Optional header image (relative to `static/img/` folder).
header:
  caption: ""
  image: ""
---

**Academic Year 2023/2024**

Visit the [UniBO website of the lecture](https://www.unibo.it/it/didattica/insegnamenti/insegnamento/2023/470093) for official and administrative details.

## Prerequisites

### A gentle introduction to [Python](https://www.python.org/) {#topic0}
This topic **wont be covered in class**.

```
if you are a student of TraTec:
  you learned the intro to Python in PBR
elif you are a student of SpecTra (1st year):
    wait for the Advanced Professional Skills Lab, next semester
else: 
  check the slides, notebooks, and 2021 video recordings
```

The materials are available at 
[https://github.com/TinfFoil/learning_dit_python](https://github.com/TinfFoil/learning_dit_python). 

Regardless of whether you attended either of the introductions, I suggest you to **do (or re-visit) all the exercises ASAP**.

<!---
#### 1. Introduction to Python scripting
* The [notebook](https://github.com/albarron/academic-kickstart/blob/master/files/week_01/Python4Poets.ipynb) for Python for Poets
* The gate to [Genesis](https://github.com/albarron/academic-kickstart/blob/master/files/week_01/genesis.txt)
-->

## Course contents

Whereas the contents could be (slightly) adapted according to the students skills and interests, the general structure of the course is as follows.

<!---
* [Lecture Notes](https://github.com/albarron/academic-kickstart/blob/master/files/week_01/coli_2020_notes.pdf)
-->

### 1. Introduction to Natural Language Processing
* \[02/10/23\] [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_01/01_nlp_handout.pdf)


### 2. Words and the vector space model

* \[03/10/23\] [Slides on tokens](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_01/02_nlp_handout.pdf) 
* \[03/10/23\] [Notebook on tokens and normalisation](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_01/02_dit_nlp_words.ipynb)
* \[09/10/23\] [Slides on VSM](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_02/03_nlp_handout.pdf) 
* \[09/10/23\] [Notebook on VSM](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_02/03_dit_nlp_tokens.ipynb)
* \[10/10/23\] [Slides on RB sentiment (+ naive bayes)](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_02/04_nlp_handout.pdf) 
* \[10/10/23\] [Notebook on RB sentiment](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_02/04_dit_nlp_rulebasedsentiment.ipynb)


### 3. Naïve Bayes
* \[10/10/23\] [Slides on Naïve Bayes](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_02/04_nlp_handout.pdf)
* \[16/10/23\] [Notebook on Naïve Bayes](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_03/05_dit_nlp_naivebayes.ipynb)


### 4. Word vectors
* \[17/10/23\] [Slides on tf-idf](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_03/06_nlp_handout.pdf)
* \[17/10/23\] [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_03/06_dit_nlp_tf-idf.ipynb)
 

### 5. From Word Counts to Meaning
* \[23/10/23\] [Slides introducing topic modelling](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_04/07_dit_nlp_handout.pdf)
* \[23/10/23\] [Notebook on topic modelling](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_04/07_dit_nlp_topicmodeling.ipynb) 
* \[24/10/23\] [Slides introducing LSA and SVD](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_04/08_dit_nlp_handout.pdf)
* \[24/10/23\] [Notebook on LSA](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_04/08_dit_nlp_lsa.ipynb)

### 6. Training and Evaluation
* \[30/10/23\] [Slides on training and evaluation](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_05/09_dit_nlp_handout.pdf)
* \[30/10/23\] [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_05/09_dit_nlp_traineval.ipynb)


 <!-- ### Intermezzo  -->

### 7. Intro to NN
* \[31/10/23\] [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_05/10_dit_nlp_handout.pdf) on the perceptron
* \[31/10/23\] [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_05/10_dit_nlp_nn.ipynb) on the perceptron
* \[06/11/23\] [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_06/11_dit_nlp_handout.pdf) introducing neural networks and keras
* \[06/11/23\] [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_06/11_dit_nlp_backprop.ipynb) introducing neural networks and keras

### 8. Word Embeddings
* \[07/11/23\] [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_06/12_dit_nlp_handout.pdf) on word2vec
* \[13/11/23\] [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_07/13_dit_nlp_handout.pdf) hands on word embeddings
* \[13/11/23\] [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_07/13_dit_nlp_embeddings.ipynb)
  

### 9. Doc2Vec
* \[14/11/23\] [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_07/14_dit_nlp_handout.pdf)
* \[14/11/23\] [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_07/14_dit_nlp_d2v.ipynb)
* \[14/11/23\] [Project reminder](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_07/14_dit_nlp_projects.pdf)

<!-- THIS WAS NOT GIVEN SINCE LAST YEAR
### 10. Visualisation
  I have decided not to offer this lecture anymore
* \[13/04/22\] Slides on visualization
* \[13/04/22\] Notebook
 -->

### 10. Convolutions for  text
* \[20/11/22\] [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_08/15_dit_nlp_handout.pdf)
* \[20/11/23\] [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_08/15_dit_nlp_cnn.ipynb)


### 11. Text is Sequential / LSTM
* \[21/11/23\] [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_08/16_dit_nlp_handout.pdf) on RNN
* \[21/11/23\] [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_08/16_dit_nlp_rnn.ipynb) on  RNN
* \[27/11/23\] [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_09/17_dit_nlp_handout.pdf) on BiRNN and LSTM
* \[27/11/23\] [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_09/17_dit_nlp_brnn.ipynb) on BiRNN 
* \[27/11/23\] [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_09/17_dit_nlp_lstm.ipynb) on LSTM

### 12. Text generation
* \[28/11/23\] [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_09/18_dit_nlp_handout.pdf) on characters and generation
* \[28/12/23\] [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_09/18_dit_nlp_chars.ipynb) on characters
* \[28/12/23\] [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_09/18_dit_nlp_lstm-gen.ipynb) on generation

<!-----
**The topics/timing from here are indicative and subject to (continuous) 
modification**
----->
### 13. Intro to Seq2Seq and Transformers ; Closing Remaks
<!--
* \[20/12/22\] [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_10/19_dit_nlp_handout.pdf) for part one
* \[22/12/22\] [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_10/20_dit_nlp_handout.pdf) for part two
 -->
<!-- ### 14. Closing Remarks -->

<!-- * \[22/12/22\] -->
<!---
* \[11/05/22\] [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_10/20_dit_nlp_handout.pdf)
-->

<!-- 
* \[04/05/22\] [Notebook on characters
* \[04/05/22\] [Notebook on generation -->
 
<!-- #### Lecture notes

These lecture notes are just a supporting materials and, conditions allowing, they will be completed throughout the course.

Download the file [here](https://github.com/albarron/academic-kickstart/raw/master/files/coli/dit_coli_notes.pdf)(last update: 26 February, 2021)
 -->
<!---
#### Beyond the course

##### Links to diverse corpora
* A recently [released corpus](https://www.english-corpora.org/corona/) with texts on COVID-19
* A [repository](https://github.com/karthikncode/nlp-datasets) with a list of interesting corpora
* Another [list](https://nlpforhackers.io/corpora/) of interesting corpora (incl. scripts from The Simpsons)
* Yet [another list](https://devopedia.org/text-corpus-for-nlp) and discussion on what is a good corpus (with many more links to resoucces)
* Google's dataset search [website](https://datasetsearch.research.google.com/)

##### Some interesting papers involving corpora creation
* [The Uppsala Corpus of Student Writings: Corpus Creation, Annotation, and Analysis](https://www.aclweb.org/anthology/L16-1509/)
* [An Evaluation Framework for Plagiarism Detection](https://www.aclweb.org/anthology/C10-2115/)
* [Constructing Corpora for the Development and Evaluation of Paraphrase Systems](https://www.mitpressjournals.org/doi/abs/10.1162/coli.08-003-R1-07-044)
* [The Web as a Parallel Corpus](https://www.mitpressjournals.org/doi/abs/10.1162/089120103322711578)
* [Building Gold Standard Corpora for Medical Natural Language Processing Tasks](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3540456/)
* [Mining Parallel Corpora from Sina Weibo and Twitter](https://www.mitpressjournals.org/doi/full/10.1162/COLI_a_00249)
* [Corpus Creation and Analysis for Named Entity Recognition in Telugu-English Code-Mixed Social Media Data](https://www.aclweb.org/anthology/P19-2025/)

##### Some quick guides to build corpora
* A [quick guide](https://www.kdnuggets.com/2017/11/building-wikipedia-text-corpus-nlp.html) on constructing corpora from the Wikipedia
* [Gensim's guide](https://radimrehurek.com/gensim/corpora/textcorpus.html) to build corpora with dictionaries
-->

## <a id="projects"></a>Projects

The [evaluation](#evaluation) is based on a project. Look for inspiration, in the [projects presented in previous years](#nlp_projects)

### Some project ideas


Whereas you are supposed to apply the acquired knowledge on a problem of your 
own interest, here are some ideas, in case you find yourself lost (consider 
them as sketches for you to elaborate further).

\[if you had seen a project proposal which is not here anymore, it means that 
the proposal belongs to a previous edition of the lesson and it has been 
(partially) addressed already. You can visit previous editions of the lesson's 
website for reference.\]

#### Gastronomy 


1. **What do restaurants in Romagna serve?**

    We have a dataset of menus from 200+ restaurants, for a total of 7000+ 
    entries. We would like to obtain a cluster of dishes and main ingredients 
    (e.g. 'cappelletti' vs. 'lasagne', regardless of what else is in the dish), 
    with frequencies of each item and possibly being able to navigate / list 
    all the variations. The concept of "ingredient" requires extracting and 
    normalizing words (e.g. lasagna = { lasagna, lasagne, lasagnetta } ).

    After this step, a language model should be built to perform 
    auto-completion. Given the dataset of menus to build a language model and a 
    demo command line app to use it to predict or suggest the next word(s).

    
2. **Cooking is hard: predicting the level difficulty of a recipe.**

    Given a recipe, including the ingredients and the process to cook a dish, 
    determine automatically it difficulty of preparation (and eventually, the 
    preparation time).
    
#### Hate Speech


1. **Dataset detective: where does this instance come from?**

    In this project, you will train a model to try to identify the dataset an instance comes from rather than the actual task it is intended to. 
    (a) Train and evaluate  one-vs-the-rest models for each of the four datasets.
    (b) Train and evaluate a multi-class model for all instances in all four datasets.
    (c) Repeat (a) and (b) but this time consider only positive (negative) instances    
    (d) Analyse the outcome: can you build a classifier that differentiates datasets? 
    The four datasets are on [hate speech and offensive language](https://github.com/t-davidson/hate-speech-and-offensive-language/tree/master/data) (2 partitions), [aggression](https://github.com/kmi-linguistics/trac-1), and [toxicity](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data).
    
#### Do not translate

1. **Identifying translated fragments in Wikipedia and the press**

    Given a pair of Wikipedia or news paper articles, spot those text fragments 
    that they have in common, because one is a translation from the other or 
    because they come from a common source.
    
2. **Identifying translations by non-native speakers**

    Given a text that has been presumably translated, identify whether the 
    person that carried out the work is a native speaker of the target language.

3. **Identifying the L2 level for a text**

    Create a model to score the complexity/readability/comprehensibility for a student at a given L2 level. The scores are A1, A2, B1, B2, C1 and C2. This is an ordinal regression task.


#### Shared Tasks

**SemEval 2024** 

This year there are 12 tasks at 
[SemEval](https://semeval.github.io/SemEval2024/tasks). I recommend to have a 
look at:

1. [Task 8](https://github.com/mbzuai-nlp/SemEval2024-task8) Multigenerator, 
Multidomain, and Multilingual Black-Box Machine-Generated Text Detection

    It offers tasks on the identification of machine-generated text with 
    different levels of complexity

2. [Task 10](https://lcs2.in/SemEval2024-EDiReF/): Emotion Discovery 
and Reasoning its Flip in Conversation (EDiReF)

    It offers two tasks on identifying the emotion of a utterence and of 
    different utterences within a dialogue

**CLEF 2024**

[CLEF](http://clef2024.clef-initiative.eu) focuses on information retrieval and 
access in multilingual and multimodal settinds. Consider:

1. [CheckThat!](https://checkthat.gitlab.io/clef2024/) lab on Checkworthiness, 
Subjectivity, Persuasion, Roles, Authorities and Adversarial Robustness 

    It offers tasks on identifying the checkworthiness of a text (+image) item, 
    the level of subjectivity of a sentence (incl. Italian), and the use of 
    persuasion in text, among others.
    
2. [Exist]() lab on sEXism Identification in Social neTworks

    Decide whether a tweet is sexist (or describes a sexist behaviour), the 
    intention of the tweet and the type of sexism.

(the tasks are still in the shaping stage)
    

#### _Standard_ research


* Performing research on propaganda identification in other languages than English. For inspiration, see this [IPM paper](https://www.scopus.com/record/display.uri?eid=2-s2.0-85065627668&origin=inward&txGid=9caa756c9a67cff1f3ae84fa6a79bfd2), this [EMNLP paper](https://www.aclweb.org/anthology/D19-1565/), or this [SemEval shared task](https://propaganda.qcri.org/semeval2020-task11/index.html)
* Estimating the complexity of a text for a non-native speaker. For inspiration, see [READ-IT](http://www.italianlp.it/demo/read-it/)
* Analysing the quality of Wikipedia articles across languages


<!---
**Are you defending on the first/second appello**? Why not turning your project into a [CLIC-it](http://clic2020.ilc.cnr.it/en/home-2/) paper? The deadline is on 15/07/2020.
-->

## Readings/Bibliography

### Core

* Hobson Lane, Cole Howard, Hannes Hapke (2019). [Natural Language Processing in Action Understanding, analyzing, and generating text with Python](https://www.manning.com/books/natural-language-processing-in-action). Manning Publications.

### Optional

* Dan Jurafsky and James H. Martin. [Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/). 3rd ed. draft. Dec, 2020

* Dirk Hovy. 2021. [Text Analysis in Python for Social Scientists](https://www.cambridge.org/core/elements/abs/text-analysis-in-python-for-social-scientists/BFAB0A3604C7E29F6198EA2F7941DFF3). Cambridge University Press. 2021

* Steven Bird, Ewan Klein, and Edward Loper. [Natural Language Processing with Python](http://www.nltk.org/book/)
* Yoav Goldberg. (2017). [Neural Network Methods for Natural Language Processing](https://www.morganclaypool.com/doi/abs/10.2200/S00762ED1V01Y201703HLT037) (G. Hirst, ed.). Morgan & Claypool Publishers.
* Emily M. Bender (2013). [Linguistic Fundamentals for Natural Language Processing: 100 Essentials from Morphology and Syntax Synthesis](https://www.morganclaypool.com/doi/abs/10.2200/s00493ed1v01y201303hlt020). Lectures on Human Language Technologies. Morgan & Claypool Publishers.
* Kenneth Ward Church. [Unix for poets](https://web.stanford.edu/class/cs124/kwc-unix-for-poets.pdf).

## Teaching methods

The course is a combination of seminar and practical sessions. In either case, active participation of the students is expected. Assuming you know the basics of programming (e.g., by completing the python course in [Topic 0](#topic0)) we will cover a (practical) description of diverse models and tasks

In order to succeed, the student has to carry our regular homework, which comes in the form of small exercises.



## Evaluation {#evaluation}

The student will work on addressing a problem within her **own research** interests with the knowledge acquired during the course. Upon agreement of the topic, the student will work on solving the problem and will produce a written report.

**_The final evaluation will be computed as a combination of both report and the oral exam around it._**


### Important points

* Your project should be submitted **1 week before the appello** to be considered valid.
* Do you want to target **30L**? Conference quality is a good way (but it is not the only one!). Talk to me well in advance if you aim this, as it would require my own heavy commitment to reach the necessary quality.



## Teaching tools

Seminars will be carried out with slides and coding will be carried out with jupyter notebooks. Continuous exercises will be carried out.

## Office hours

See my [UniBO website](https://www.unibo.it/sitoweb/a.barron)

## Previous final projects (submitted by September 2022) {#nlp_projects}

### 2021-2022

* **Hate Speech Detection in Incel Online Spaces**<br />
  Student: Gajo, P.<br />
  [{{< fa file-pdf >}}](https://github.com/albarron/academic-kickstart/raw/master/files/coli/projects2022/dit_coli2022_project_gajo.pdf)

* **Fishing for catfishes: using a model trained on Twitter data to predict
author gender in Reddit posts**<br />
  Student: Kovacs, M. <br />
  [{{< fa file-pdf >}}](https://github.com/albarron/academic-kickstart/raw/master/files/coli/projects2022/dit_coli2022_project_kovacs.pdf)

### 2020-2021

* **Assessing Semantic Similarity between Original Texts and Machine Translations**<br />
  Student: Hopkins, D.<br />
  [{{< fa file-pdf >}}](https://github.com/albarron/academic-kickstart/raw/master/files/coli/projects2021/dit_coli2021_project_hopkins.pdf)

* **Definition extraction on food-related Wikipedia articles**<br />
  Student: Martinelli, M.<br />
 <!-- \[[pdf]()\]-->
  
* **Identifying Characters’ Lines in Original and Translated Plays. The case of
  Golden and Horan’s Class**<br />
  Student: Galletti, E.<br />
  [{{< fa file-pdf >}}](https://github.com/albarron/academic-kickstart/raw/master/files/coli/projects2020/dit_coli2020_project_galletti.pdf)

* **Classifying An Imbalanced Dataset with CNN, RNN, and LSTM**<br />
  Student: Yu, X.<br />
  [{{< fa file-pdf >}}](https://github.com/albarron/academic-kickstart/raw/master/files/coli/projects2020/dit_coli2020_project_yu.pdf)

### 2019-2020

* **AriEmozione: Identifying Emotions in Opera Verses**<br />
  Students: Fernicola F. and Zhang S.<br />
  Developed under [CRICC](https://site.unibo.it/cricc/it);
  published in [CLiC-it 2020](http://ceur-ws.org/Vol-2769/)<br />
  [{{< fa file-pdf >}}](http://ceur-ws.org/Vol-2769/paper_58.pdf)
  [{{< fa video >}}](https://vimeo.com/515280902)

* **UniBO@AMI: A Multi-Class Approach to Misogyny and Aggressiveness
  Identification on Twitter Posts Using AlBERTo**<br />
  Student: Muti, A.<br />
  Top-performing model in [Evalita's 2020
  AMI](https://amievalita2020.github.io/) shared task<br />
  [{{< fa file-pdf >}}](http://ceur-ws.org/Vol-2765/paper117.pdf)
  [{{< fa video >}}](https://vimeo.com/487827751)



## For the record

You can visit previous editions of the course:

2022-2023 - [Natural Language Processing]({{< ref "teaching/natural-language-processing2022/_index.md">}}) - 6 cfu <br />
2021-2022 - [Computational Linguistics]({{< ref "teaching/computational-linguistics2021/_index.md">}}) - 6 cfu <br />
2020-2021 - [Computational Linguistics]({{< ref "teaching/computational-linguistics2021/_index.md">}}) - 6 cfu <br />
2019-2020 - [Computational Linguistics]({{< ref "teaching/computational-linguistics2020/_index.md">}}) - 6 cfu <br />
