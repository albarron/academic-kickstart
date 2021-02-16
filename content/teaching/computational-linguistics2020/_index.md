---
title: Computational Linguistics. 

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

**Academic Year 2019/2020**

**This is not the current edition of this lecture. Jump 
[here](https://albarron.github.io/teaching/computational-linguistics/) instead**

## Learning outcomes

The student will learn the basic theoretical aspects of computational linguistics/natural language processing and will acquire practical skills to perform from tokenization and vectorization to the computation of similarities and supervised models (e.g., for topic identification, structural analysis, meaning analysis).

## Course contents

Whereas the contents could be (slightly) adapted according to the students skills and interests, the general structure of the course will be as follows.

#### 0. Introduction to Computational Linguistics

* [Lecture Notes](https://github.com/albarron/academic-kickstart/blob/master/files/week_01/coli_2020_notes.pdf)
* [Slides](https://github.com/albarron/academic-kickstart/blob/master/files/week_01/01_coli_2020.pdf)

#### 1. Introduction to Python scripting
* The [notebook](https://github.com/albarron/academic-kickstart/blob/master/files/week_01/Python4Poets.ipynb) for Python for Poets
* The gate to [Genesis](https://github.com/albarron/academic-kickstart/blob/master/files/week_01/genesis.txt)

#### 2. Words and vector space model
* [Lecture Notes](https://github.com/albarron/academic-kickstart/blob/master/files/week_02/coli_2020_notes.pdf) as after finishing the second week..
* The [notebook](https://github.com/albarron/academic-kickstart/blob/master/files/week_02/02_Prepro.ipynb) for preprocessing
* The [notebook](https://github.com/albarron/academic-kickstart/blob/master/files/week_02/03_Tokens.ipynb) for tokens and the space model
* [Slides](https://github.com/albarron/academic-kickstart/blob/master/files/week_02/02_coli_2020.pdf) on tokens
* [Slides](https://github.com/albarron/academic-kickstart/blob/master/files/week_02/03_coli_2020.pdf) on the vector space model and sentiment analysis


#### 3. Naive Bayes
* [Slides](https://github.com/albarron/academic-kickstart/blob/master/files/week_03/04_coli_2020.pdf)
* [notebook](https://github.com/albarron/academic-kickstart/blob/master/files/week_03/04_NaiveBayes.ipynb)

#### 4. Word vectors
* [Slides](https://github.com/albarron/academic-kickstart/blob/master/files/week_04/05_coli_2020.pdf)
* [notebook](https://github.com/albarron/academic-kickstart/blob/master/files/week_04/05_tf-idf.ipynb)

#### 5. From Word Counts to Meaning
* [Slides](https://github.com/albarron/academic-kickstart/blob/master/files/week_05/06_coli_2020.pdf)
* [notebook](https://github.com/albarron/academic-kickstart/blob/master/files/week_05/06_topicmodeling.ipynb)

#### 6. Training and Evaluation
* [Slides](https://github.com/albarron/academic-kickstart/blob/master/files/week_05/07_coli_2020.pdf)
* [notebook](https://github.com/albarron/academic-kickstart/blob/master/files/week_05/07_trainingandevaluating.ipynb)

#### 7. Intro to LSA
* [Slides](https://github.com/albarron/academic-kickstart/blob/master/files/week_06/08_coli_2020.pdf)
* [notebook](https://github.com/albarron/academic-kickstart/blob/master/files/week_06/08_lsa.ipynb)

#### 8. Intro to NN
* [Slides](https://github.com/albarron/academic-kickstart/blob/master/files/week_07/09_coli_2020.pdf) about the perceptron
* [Slides with "funny" drawings](https://github.com/albarron/academic-kickstart/blob/master/files/week_07/09_coli_2020_edited.pdf) about the perceptron
* [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/week_07/09_nn.ipynb)a about the perceptron
* [Slides](https://github.com/albarron/academic-kickstart/blob/master/files/week_07/10_coli_2020-handout.pdf) for the intro to neural networks
* [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/week_07/10_backprop.ipynb) introducing neural networks and keras

#### 9. Word Embeddings
* [Slides](https://github.com/albarron/academic-kickstart/blob/master/files/week_08/11_coli_2020-handout.pdf)
* [Slides](https://github.com/albarron/academic-kickstart/blob/master/files/week_08/12_coli_2020-handout.pdf) (hands on)
* [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/week_08/11_embeddings.ipynb)

#### 10. Visualisation
* [Slides](https://github.com/albarron/academic-kickstart/blob/master/files/week_09/13_coli_2020-handout.pdf)
* [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/week_09/12_viz.ipynb)

#### 11. From document representations, towards sequences
* [Slides](https://github.com/albarron/academic-kickstart/blob/master/files/week_09/14_coli_2020-handout.pdf)

#### 12. Convolutions for text
* [Slides](https://github.com/albarron/academic-kickstart/blob/master/files/week_10/15_coli_2020-handout.pdf)
* [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/week_10/13_cnn.ipynb)

#### 12. Text is Sequential
* [Slides](https://github.com/albarron/academic-kickstart/blob/master/files/week_10/16_coli_2020-handout.pdf)
* [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/week_10/14_rnn.ipynb)

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

## Projects

**Notice** If you opt for turning your project into the participation to some shared task, it is **alright** if more than one person targets the same task.

### Submitted projects (up to February 2021) {#coli20_projects}

* **AriEmozione: Identifying Emotions in Opera Verses**<br />
  Students: Fernicola F. and Zhang S.<br />
  Developed under [CRICC](https://site.unibo.it/cricc/it);
  published in [CLiC-it 2020](http://clic2020.ilc.cnr.it/it/home/)<br />
  \[[pdf](http://ceur-ws.org/Vol-2769/paper_58.pdf)\]

* **UniBO@AMI: A Multi-Class Approach to Misogyny and Aggressiveness
  Identification on Twitter Posts Using AlBERTo**<br />
  Student: Muti, A.<br />
  Top-performing model in [Evalita's 2020
  AMI](https://amievalita2020.github.io/) shared task<br />
  \[[pdf](http://ceur-ws.org/Vol-2765/paper117.pdf)\]
  \[[video](https://vimeo.com/487827895)\]

* **Identifying Characters’ Lines in Original and Translated Plays. The case of
  Golden and Horan’s Class**<br />
  Student: Galletti, E.

* **Classifying An Imbalanced Dataset with CNN, RNN, and LSTM**<br />
  Student: Yu, X.


### Some project alternatives
* Performing a small research project taking advantage of the COVID-19 corpus (see Beyond the course)
* Participating to some of the [EVALITA 2020](http://www.evalita.it/2020/tasks) shared tasks. There is [age and gender profiling](https://sites.google.com/view/tag-it-2020), [misogyny identification](https://amievalita2020.github.io/), and  [complexity evaluation](https://sites.google.com/view/accompl-it/home-page?authuser=0), among many others.
* Performing research on propaganda identification in other languages than English. For inspiration, see this [IPM paper](https://www.scopus.com/record/display.uri?eid=2-s2.0-85065627668&origin=inward&txGid=9caa756c9a67cff1f3ae84fa6a79bfd2), this [EMNLP paper](https://www.aclweb.org/anthology/D19-1565/), or this [SemEval shared task](https://propaganda.qcri.org/semeval2020-task11/index.html)
* Estimating the complexity of a text for a non-native speaker. For inspiration, see [READ-IT](http://www.italianlp.it/demo/read-it/)
* Analysing the quality of Wikipedia articles across languages

**Are you defending on the first/second appello**? Why not turning your project into a [CLIC-it](http://clic2020.ilc.cnr.it/en/home-2/) paper? The deadline is on 15/07/2020.

### 2020 students and their project

| students																| Project name   |  Status 				| Call |
-------------------------------------	| ------------------- | ---------------- | -------
Alfieri, A												| TBD									| TBD							| TBD	|
Compagnoni, A			| TBD									| TBD							| TBD	|
Contarino, A	  | TBD									| TBD							| TBD	|
Fabbri, E			  | TBD									| TBD							| TBD	|
Fernicola, F		| AriEmotion				| submitted		| Sep	2020 |
Ferraiuolo, M	    	| TBD									| TBD							| TBD	|
Galletti, E		 	    | Theatre's character recognition	| submitted							| Feb 2021	|
Giannoni, L							| TBD									| TBD							| TBD	|
Guarino, E							| TBD									| TBD							| TBD	|
Ippoliti, C							| TBD									| TBD							| TBD	|
Martinelli, M						| TBD									| TBD							| TBD	|
Moro, E									| TBD									| TBD							| TBD	|
Muti, A									| Evalita's [AMI (task A)](https://amievalita2020.github.io)	| submitted	| Sep |
Norova-Lukina, V				| Cognates for text intercomprehension				| green flag							| TBD	|
Polverino, F						| TBD									| TBD							| TBD	|
Ravanelli, S						| TBD									| TBD							| TBD	|
Tedesco, N							| Geolocalised COVID-19 Twitter Discussion Explorer	| Tentative		| TBD	|
Terenzi, L							| TBD									| TBD							| TBD	|
Vázquez C, A	| TBD			| TBD							    | TBD	|
Wang, X									| TBD									| TBD							| TBD	|
Yu, X X (Catherine)			| Focused hate-speech during the pandemia	| submitted							| Feb 2021	|
Zhang, S								| AriEmotion				| submitted		| Sep 2020	|

## Readings/Bibliography

### Core

* Hobson Lane, Cole Howard, Hannes Hapke (2019). Natural Language Processing in Action Understanding, analyzing, and generating text with Python. Manning Publications.
* Steven Bird, Ewan Klein, and Edward Loper. [Natural Language Processing with Python](http://www.nltk.org/book/)

### Optional

* Dan Jurafsky and James H. Martin. Speech and Language Processing (3rd ed. draft) Draft chapters in progress, October 16, 2019
* Yoav Goldberg. (2017). Neural Network Methods for Natural Language Processing (G. Hirst, ed.). Morgan & Claypool Publishers.
* Emily M. Bender (2013). Linguistic Fundamentals for Natural Language Processing: 100 Essentials from Morphology and Syntax Synthesis Lectures on Human Language Technologies. Morgan & Claypool Publishers.
* Kenneth Ward Church. Unix for poets.

## Teaching methods

The course is a combination of seminar and practical sessions. In either case, active participation of the students is expected. We will start with an introduction to the Python programming language and follow with a (practical) description of diverse models and tasks.

Attendance to a minimum of 70% of the lessons is a must.

## Assessment methods

The student will work on addressing a problem within her **own research** interests with the knowledge acquired during the course. Upon agreement of the topic, the student will work on solving the problem and will write a written report. A poster session will be organized at the end of the course in which the students will present their research work.

**_The final evaluation will be computed as a combination of both report and poster presentation._**

## Teaching tools

Seminars will be carried out with slides and coding will be carried out with jupyter notebooks. Continuous exercises will be carried out.

## Office hours

TBD
