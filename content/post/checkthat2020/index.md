---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Checkthat2020"
subtitle: ""
summary: "A personal summary of the ChechThat! 2020 sessions at CLEF 2020"
authors: []
tags: []
categories: []
date: 2020-09-23T12:31:45+02:00
lastmod: 2020-09-23T12:31:45+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
## My personal take of CheckThat! 2020

*Disclaimer*. I am one of the organisers of [CheckThat! 2020](https://sites.google.com/view/clef2020-checkthat).  This is my very personal overview of what happened during the three parallel sessions. During all three sessions I was either chairing, hosting, and live-tweeting (often at the same time). I might have missed important details. I might show biased impressions

### Session 1. Overview and Tasks 1 and 5

### Session 2. Tasks 2, 3, and 4

### Session 3.  Invited speakers and a round table

The closing session of CheckThat! 2020 features three guest speakers: 
- David Corney, from [Full Fact](https://fullfact.org) (UK)
- Rubén Míguez, from [Newtral](https://www.newtral.es) (Spain)
- Moath Althaher, from [Fatabyyano](https://fatabyyano.net/) (Jordan)

We targetted to bring them together to know about the fact-checking practices from the perspective of leading organisations in the field of fact-checking in differtent markets. 

#### D. Corney. Making fact checks work harder: claim matching at Full Fact

David started with a very clear statement about what is important for a journalist in Full Fact: 

1. What is the improtant claim to check today?
2. Is this new claim by that person already checked?
3. I want to check claims fast!

He explains that, at FullFact, they receive about 100k sentences from the UK alone every day and they usually have 100 fact checks to keep track of. That means 10M pairwise comparisons out of which very few actually match. 

In order to find matches, triggering interesting findings, they fuse multiple signals, including [sentence BERT](https://github.com/UKPLab/sentence-transformers) similarities, [BM25 scores](https://en.wikipedia.org/wiki/Okapi_BM25), and the amoount of shared entities, among others. 

Whereas based in the UK, Full Fact collaborates with organisations such as [Africa Check](https://africacheck.org) and the Argentinian [Chequeado](https://chequeado.com).

#### R. Míguez Newtral. ClaimHunter - an unattended claim detection service for fact-checkers

Different from other organisations (amon them the other two invited to this event), Newtral is a *for profit* one. Fact-checking is only one of their activities. They are an independent TV producer with 80+ employees and TV shows in Spanish television. 

As for their fact-checking efforts, an interesing aspect is that they do not focus on the Web only. They record and transcribe videos from the Spanish television and pass such transcriptions through a selection process. Interestingly, punctuation is a key aspect for them, because they fact-check sentences. 

According to the numbers, only 1.39% of the sentences are relevant and check-worthy. The automatic filtering performed saves the time of the journalists by an estimated 50%. 

They have another channel to reach the audience: whatspapp. They are able to match claims multilingually (e.g., Spanish, Catalan, Gallegan) and, if they believe they have fact-checked  the user claim already, they just answer to it. When asked about the high risk of answering automatically, Ruben argues that not answering is worst. They indeed shoot the answer, but with a warning, telling the user that this is the result of an automatic process and openind the door for user feedback.

Among the technology that enables their fact-checking process, they have [Elastic Search](https://www.elastic.co/elasticsearch/) and [language-agnostic BERT](https://ai.googleblog.com/2020/08/language-agnostic-bert-sentence.html).

#### M. Althaher. The philosophy of Fake News - The Big Questions! 

Moath started with an important (and truth) claim: MENA is not one single category. It is not one single market. People are quite different and have different interests in the Gulf, Levant, Egypt, Magreb. The region with the highest number of fake news is Egypt. One cause is simply the amount of web users. 

He explains an interesting example of fake news that remained around for long time: a claim that people in Italy were massively killing each other during the beginning of the COVID-19 crisis! As worrisome as it sounds, there was another even more harmful: that muslims were not at risk with COVID. 


### Round Table



could be other reasons. 

.  **rgewho do fact checking as a 
Other than 
int of view of