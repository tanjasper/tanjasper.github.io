---
title: "Parameters or Privacy: A Provable Tradeoff Between Overparameterization and Membership Inference"
authors: <b>J. Tan</b>, B. Mason, H. Javadi, R.G. Baraniuk
collection: publications
excerpt: 'Theoretical and empirical evidence showing how increasing the parameters of a regression model increases its vulnerability to membership inference attacks for various data settings.'
date: 2022-11-29
venue: 'Neural Information Processing Systems (NeurIPS)'
paperurl: 'https://arxiv.org/pdf/2202.01243.pdf'
---
**Abstract:** 
A surprising phenomenon in modern machine learning is the ability of a highly {\em overparameterized} model to generalize well (small error on the test data) even when it is trained to memorize the training data (zero error on the training data). This has led to an arms race towards increasingly overparameterized models (c.f., deep learning). In this paper, we study an underexplored hidden cost of overparameterization: the fact that overparameterized models are more vulnerable to {\em privacy attacks}, in particular the {\em membership inference} attack that predicts the (potentially sensitive) examples used to train a model. We significantly extend the relatively few empirical results on this problem by theoretically proving for an overparameterized linear regression model with Gaussian data that the membership inference vulnerability increases with the number of parameters. Moreover, a range of empirical studies indicates that more complex, nonlinear models exhibit the same behavior. Finally, we study different methods for mitigating such attacks in the overparameterized regime, such as noise addition and regularization, and conclude that simply reducing the parameters of an overparameterized model is an effective strategy to protect it from membership inference without greatly decreasing its generalization error.

**Links:**
[Paper](https://arxiv.org/pdf/2202.01243.pdf)
