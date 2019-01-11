# Project reports

This repository contains typeset reports for some of my favourite project I have done during my studies.

I describe the projects I have included below.

Some of the projects are a result of teamwork and I have mentioned my collaborators in the descriptions of those.

## Machine Learning Practical -- Differentiable IQ question answering

As a part of the Machine Learning Practical course in the University of Edinburgh, Miroslav Trifonov, Kamen Brestnichki
and I designed and implemented a differentiable model that can solve a class of simple visual IQ questions
called [Raven Progressive Matrices](https://en.wikipedia.org/wiki/Raven%27s_Progressive_Matrices).
  
As part of the course, we had to produce two reports. [The first one](mlp/MLP_Coursework_3.pdf) motivates our choice
of task and dataset and contains some preliminary experiments and [the second one](mlp/MLP_Coursework_4.pdf)
describes our method and experiments. Our code can be found [here](https://github.com/KamenB/mlp-03)

## Bachelor Thesis -- RNNs for Dasher: Making text entry for the disabled twice as fast
**Under the supervision of Dr Iain Murray**

[Dasher](http://www.inference.org.uk/dasher/) is a continuous-gesture text-entry system developed in Cambridge
in 2005. It is particularly suitable for people with certain disabilities and is used by a small minority of people.
For its operation it relies on a character-level language model -- a model that outputs a probability for the next
character in a sequence given all of the preceding characters.

At the time of writing, the state-of-the-art in language modelling was achieved using Recurrent Neural Network-based
language models. For my project, I investigated the sensibility and feasibility of the idea of incorporating this type
of language model in the Dasher system.

I designed and carried out experiments that compared RNN-based models to the language model currently employed in Dasher
in terms of language modelling capacity as well as computational requirements.

My thesis can be found [here](thesis_b/MInf_Project_Part_1.pdf) and my code and experimental results
[here](https://github.com/YasenPetrov/char-rnn-experiments) and
[here](https://github.com/YasenPetrov/rnn-experiment-storage).

## Accelerated Natural Language Processing

University of Edinburgh, Academic year 2018/2019, taught by Prof. Sharon Goldwater and Henry Thompson

### Methods for word embeddings using occurence counts in tweets

In collaboration with Marko Smilevski

For this assignment we were tasked with exploring problems with distributed word embeddings asn similarity metrics. We chose to look
into the hubness problem -- the phenomenon that often times when measuring similarities between words using distributed
embeddings we see that some high-frequency words are "closer" to a disproportionally large number of words.

We explore several different methods for producing embeddings and computing similarities. We end up with some interesting
findings which possibly explain some claims we have found in literature on the subject. Our rather short (due to
a hard limit in the assignment formulation) report can be found [here](anlp/anlp_cw3.pdf)

[//]: <> (### Character-level language modelling)

[//]: <> (In collaboration with Mihaela Stoian We implemented a simple character-level n-gram language model. We investigated different smoothing techniques and ways to generate text. Also, we tried to derive a metric for the similarity between languages based on n-gram frequencies. Our report can be found)


## Parallel and Concurrent Programming (National University of Singapore)

### Distributed Othello agent

I had to build and parallelize an agent for a slightly modified version of the classical board game
[Othello](https://en.wikipedia.org/wiki/Reversi) (also known as Reversi).

A rather long report, detailing my work can be found [here](nus_parallel_programming/CS3211_Project_2.pdf)
