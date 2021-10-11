---
title: "C.Psyd - Research"
layout: textlay
excerpt: "C.Psyd -- Research"
sitemap: false
permalink: /research/
---

# Research

We are primarily interested in incremental language processing. Incremental language processing requires making processing decisions with incomplete information and may involve making predictions under uncertainty. We are especially interested in these topics in naturalistic broad-coverage settings, though we also occasionally use controlled experimental settings as well. To study effective processing strategies, we build computational models to predict human behavioral responses (e.g., reading times, neuroimaging data), and we analyze the strategies learned by statistical models trained on language data. 

Here are some themes and techniques that we currently work on:

**Behavioral predictions.** We can directly observe human behavior or neurological output in response to language data. Psycholinguists often attempt to make direct inferences about the underlying linguistic representations and language processing algorithms, usually using controlled experimental settings in order to make the process manageable. But this approach neglects the complex interactions that can occur between different linguistic phenomena (by its nature, controlling for confounds in an experiment requires limiting the analysis to a very small number of responses of interest). Instead, C.Psyders often build multiple computational models that condition on different input features or utilize different processing algorithms. By observing which model better predicts human data at a large scale, we can infer which kinds of representations or processing algorithms are closer to what humans do. And we can observe how different modeling decisions interact "in the wild."

**Linking hypotheses.** How can we make inferences about humans from observing language or by comparing human behavior to models? By assuming some kind of linking function! These linking hypotheses are often the product of experimental evidence from psycholinguistics combined with convenience. By studying which linking hypotheses better predict human behavior, we can derive more conclusions from our computational models and thereby make stronger claims about human processing.

**Interpretability.** We analyze the linguistic representations and processing strategies encoded in neural network models that have been trained on large amounts of language data. Probing these models tells us about the statistics of the training data. What kinds of predictions are statistically licensed under different input contexts? Studying the existence of different abstract representations can tell us which linguistic abstractions are helpful when compressing the data into the trained model. Studying the relationships between learned abstractions can tell us which abstractions occur in similar contexts and therefore are compressed similarly in the models. All of our results from this line of inquiry can provide evidence for the kinds of linguistic representations and processing strategies that are licensed by input statistics and therefore may be utilized by humans.
