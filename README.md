# Markov-HMM

In this repo, you'll find some practical examples on how using HMM's (hidden markov model). There is three main notebooks:

## 1. markov.ipynb:

This is an implementation of markov chains. We created a markov chain based on Sherlock Holmes stories where at the end we where able to generate text with the same original style. This is an example of the results:

```
0.  my dear holmes i went to bed and the note with which the crime was committed so as
1.  my dear watson i think you can find nothing against him either here in my pocket there i
2.  my dear watson i am very much so and the adventure of the musgrave ritual arthur conan doyle
3.  my dear watson i think we are a good fellow said holmes it is very essential to me
4.  my dear mycroft the brothers life is more than these folk here in spite of the door mr
5.  my dear young lady we have so much for the man was crouching at the window the card
```

## 2. HMM_with_intial_parameters.ipynb:

A practical example of predicting a teacher's mood, the goal is to leverage HMMs to forecast the teacher's emotional state based on the observed t-shirt colors worn on consecutive days without the training step (we know all the transitions and emissions values).

## 3. HMM_with_training:

The same practical example as above but this time with training step.
