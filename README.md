### Barka da zuwa!!! --> Welcome!!!

<!-- ⚠️ This README has been generated from the file(s) "blueprint.md" ⚠️-->
[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#hausa-nlp)

# Hausa Visual Genome: A Dataset for Multi-Modal English to Hausa Machine Translation


![GitHub](https://img.shields.io/github/license/hausaNLP/HausaNLP)
![GitHub](https://img.shields.io/badge/license-CCBY-yellow)


![Twitter Follow](https://img.shields.io/twitter/follow/hausanlp?label=follow&style=social)
![GitHub followers](https://img.shields.io/github/followers/hausanlp?style=social)
![visitors](https://visitor-badge.glitch.me/badge?page_id=hausanlp.hausanlp)[<img src="https://img.shields.io/badge/chat-on slack-yellow.svg?logo=slack">](https://join.slack.com/t/hausanlp/shared_invite/zt-ndbyv4td-VyhGaGgMPk0c4A2OIBk2mA) 
[<img src="https://img.shields.io/badge/visit-our site-yellow.svg?logo=web">](https://hausanlp.github.io/) 


## Welcome!

This is a repository for Hausa Visual Genome dataset, containing about 33K images and a short English and Hausa description of a section of each image. Jump straight to one of the sections below, or just scroll down to find out more.

## Table of Contents

  - [The Problem](#the-problem)
  - [Language Resources Developed](#language-resources-developed)
    - [Dataset Formats](#dataset-formats)
    - [Data Statistics](#data-statistics)
  - [Using The Dataset](#using-the-dataset)
  - [Paper(s) from this Project](#papers-from-this-project)
  - [The Team](#the-team)
  - [Contact Us](#contact-us)
  - [Glossary](#glossary)
  

## The Problem

Multi-modal Machine Translation (MMT) enables the use of visual information to enhance the quality of translations. The visual information can serve as a valuable piece of context information to decrease the ambiguity of input sentences. Despite the increasing popularity of such a technique, good and sizeable datasets are scarce, limiting the full extent of their potential. Hausa, a Chadic language, is a member of the Afro-Asiatic language family. It is estimated that about 100 to 150 million people speak the language, with more than 80 million indigenous speakers. This is more than any of the other Chadic languages. Despite a large number of speakers, the Hausa language is considered a low-resource language in natural language processing (NLP). This is due to the absence of sufficient resources to implement most of the tasks in NLP. While some datasets exist, they are either scarce, machine-generated, or in the religious domain. Therefore, there is the need to create training and evaluation data for implementing machine learning tasks and bridging the research gap in the language.


## Language Resources Developed

Hausa Visual Genome is a multimodal dataset consisting of text and
images suitable for English-to-Hausa multimodal machine translation task
and multimodal research. We selected all the English segments
(captions) of the Hindi Visual Genome along with associated images and
automatically translated them to Hausa with manual post-editing, taking
the associated images into account.

The training set contains 29K segments. Further 1K, 1.6K and 1.4K segments are
provided in a development, test and challenge test sets, respectively.

### Dataset Formats

The multimodal dataset contains both text and images. The text parts of the dataset (train and test sets) are in simple comma-delimited plain text files.

All the text files have seven columns as follows:

* Column1 - image_id
* Column2 - X
* Column3 - Y
* Column4 - Width
* Column5 - Height
* Column6 - English Text
* Column7 - Hausa Text

The image part contains the full images with the corresponding image_id as the file name. The X, Y, Width and Height columns indicate the rectangular region in the image described by the caption.

### Data Statistics

The statistics of the current release is given below.

| Dataset | Segments | English Words | Hausa Words |
| :--- | ---: | ---: | ---: |
| Train | 28930 | 147219 | 144864 |
| Dev | 998 | 5068 | 4978 |
| Test | 1595 | 8079 | 7952 |
| Challenge Test | 1400 | 8411 | 9514 |
| **Total** | **32923** | **168777** | **167308** |

* *The word counts are obtained after tokenization using the NLTK punkt tokenizer.*


## Using The Dataset


## Papers from this project 

The dataset description and baseline experiments paper has been accepted at the Language Resources and Evaluation Conference 2022 (*LREC2022*). The details of the paper will be provided after it has been published. Thank you.
  
 
## The Team

This is a joint collaboration between HausaNLP and researchers other international researchers currently in India, Finland, USA and The Czech Republic. HausaNLP is an open source community of academics, researchers, students, ml-engineeers, and NLP ethusiastics with passion for Hausa natural language processing.

The team involved in this project are:

| Names | Institutions |
| :--- | :--- | 
| Idris Abdulmumin | Ahmadu Bello University, Zaria - Nigeria |
| Satya Ranjan Dash | KIIT University, Bhubaneswar - India |
| Musa Abdullahi Dawud | KIIT University, Bhubaneswar - India |
| Shantipriya Parida | Silo AI, Helsinki - Finland |
| Shamsuddeen Hassan Muhammad | Bayero University, Kano - Nigeria |
| Ibrahim Sa'id Ahmad | Bayero University, Kano - Nigeria |
| Subhadarshi Panda | City University of New York - USA |
| Ondrej Bojar | Charles University, Prague - Czech Republic |
| Bashir Shehu Galadanci | Bayero University, Kano - Nigeria |
| Bello Shehu Bello | Bayero University, Kano - Nigeria |

<!--

[contributors' guidelines](CONTRIBUTING.md) and our [roadmap](../../issues/1).

-->
<!--
   - Join our [Google group](hausa-nlp@googlegroups.com)
   - To be feature on our website? send us your details via hausanlp@gmail.com and use this as a [template](https://hausanlp.github.io/author/ibrahim-said-ahmad/)

<!--
[code of conduct](CODE_OF_CONDUCT.md) in all interactions both on and offline.

-->


<!-- 
http://indigenousblogs.com/ha/
-->
  

<!-- TODO: Add last video link 

## Maintainers (Hall of Fame)

-->


## Contact us

If you want to report a problem or suggest an enhancement we'd love for you to [open an issue](../../issues) at this github repository because then we can get right on it. But you can also contact us by email (hausanlp AT gmail DOT com) or on [twitter](https://twitter.com/hausanlp).

## Thank you

Thank you so much (mun gode!) for visiting the project and we do hope that you'll join us on this amazing journey to support development of resources for Nigerian natural language processing.

## Glossary

* **Hausa**:  Hausa is a Chadic language spoken by the Hausa people, mainly within the territories of Niger and the northern half of Nigeria, and with significant minorities in Chad, Ghana, and Cameroon.

* **repository** or **repo**: a collection of documents related to your project, in which you create and save new code or content

* **Milestone**: an event or state marking a specific stage in development on the project
* **Issue**: the GitHub term for tasks, enhancements, and bugs for your projects
