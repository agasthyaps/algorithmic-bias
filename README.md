# Experiments with Reducing Algorithmic Bias in Gender Classification Systems


## Problem Statement and Motivation

Face recognition software is now built into most smart phones and several companies have released commercial software that perform automated facial analysis. Some such products include Face++, Google Image search and even automatic recognition of people in Facebook and Apple photo libraries. However, much of this technology is plagued by shortcomings, especially with respect to women or people of colour. We have seen news articles about iPhones not recognising people of colour or a simple Google search of a black man’s name returning more references to criminal activity or crime reporting. The latest gender classification report from NIST also shows that the algorithms they evaluated performed worse for female-labeled faces than male-labeled faces (Ngan et al., 2015). 

Most large scale face collection depends on face recognition algorithms. This means that any systematic error found in face detectors will inevitably affect the composition of the benchmark. As an example, the LFW dataset composed of celebrity faces is 77.5% male and 83.5% White. In response, the IARPA has released the IJB-A dataset which does not use face detectors to select images. An Algorithmic Justice League (AJL) has also been set up at MIT to combat ‘exclusionary experiences and discriminatory practices’ caused by algorithms.

A 2012 study (Klare et. al.) on mug shots found that a facial recognition algorithm trained exclusively on either African American or Caucasian faces recognized members of the race in its training set better than those of other races. The effect of the composition of the training set used surely matters.

## Overarching Aim
This project recognises that we live in a world with terribly imperfect datasets. We demonstrate how imbalance among racial groups in training data leads to poor performance in models, and we also investigate different ways that imperfect datasets can be used well and augmented in ways that improve accuracy. Our overarching aim is to improve prediction accuracy of gender classification models using images of White, Black and Asian faces.

### Sub-goals
- Compare accuracy of models trained on skewed and balanced datasets
- Explore data augmentation techniques to counteract imbalance in training data
- Use transfer learning to determine whether pre-trained image classification models can improve their accuracy when re-trained for a different task.

Agasthya Shenoy

Mehul Raje

Emma Dwight
