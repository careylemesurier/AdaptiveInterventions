# Adaptive Interventions
Analysis on data collected from an experiment aimed at assessing the effect of mental health mitigation strategies (ie. breathing exercises) on academic performance

This reaserch was done as part of my CSC 2558: Topics in Human Computer Interaction course at the University of Toronto (2021)

## Project Abstract

An experiment was conducted on a group of first year computer science students, to evaluate the effect of breathing exercises on academic performance. A written prompt, guiding participants through a focused breathing exercise, was presented to the students before they completed an online quiz question. Adaptive experimentation methods were used to sample if a student received the prompt or not, in order to evaluate the prompt’s effect. It was found that the prompt showed a slightly positive impact on the probability of a student getting the answer correct. However, the difference between the reward for each arm was not statistically significant. Also, since this experiment was not conducted in a controlled environment we have no way of knowing if the breathing exercise was actually completed. This research also aimed to evaluate the performance of the 3 algorithms; Thompson Sampling, Uniform random, and TS-PostDiff, in terms of both statistical accuracy and total reward. Since the experiment showed no statistical difference between the two arms, a simulation was created to compare the algorithms' performance. It was found that TS-PostDiff was able to effectively balance achieving statistical accuracy and optimizing total reward. 

## Files

+ ProjectReport.pdf: This file contains the written report
+ project_simulation.ipynb: python code for the simulated experiment, used to compare results of the real experiment
+ experiment_results.ipynb: python code to analyse the observed data from the experiment
