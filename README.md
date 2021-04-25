# Hackathon-2021



**Update on Going ...**



This repository stores the code and results in BioHackathon-2021, aiming to predict the stability of mutated proteins.

The descriptions of this Hackathon can be found [here](https://biohackathon.biolib.com/event/2021-protein-edition).

The data comes from this article https://www.bakerlab.org/wp-content/uploads/2017/12/Science_Rocklin_etal_2017.pdf

This our [team page](https://biolib.com/SVM2/Spaghetti-Vector-Monster-2/). Teammates: [Jiajun He](https://github.com/hejj16), [Zelin Li](https://github.com/lzlniu).

An outline of our work and result can be found [here](https://github.com/hejj16/Hackathon-2021/blob/main/Presentation_Slide.pdf).

A more detailed description is shown below.

<br/>

## Description of the task

- The main task for us is to use the amino acids sequence of mini-protein (43 a.a. length) and their secondary structure information to predict their structural stability.
- The inputs are a.a. sequence (20 kinds of standard a.a., and non-standard, in total 21 kinds) and secondary structure (E, T, H; 3 kinds) sequence.
- This is a regression task and will output the stability score change of the mutated mini-protein (a score proportion to ΔG).


## An outline of our work

We perform 2 kinds of models: Simple Machine Learning Methods and Complex Deep Learning Models with transformer and LSTMs.

### Description of Simple Machine Learning Methods



### Description of Deep Learning Models with transformer and LSTMs

