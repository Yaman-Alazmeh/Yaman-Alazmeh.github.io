---
title: "Baby Assistant research"
---


This research explores how machine learning and audio signal processing can be used to support new parents by identifying the reasons behind a baby’s cry and providing helpful,
personalized recommendations.
<br>
The system combines multiple components—audio feature extraction, classification logic, evaluation metrics,
and a simple user interface—to create an early prototype of an AI-powered baby assistant.

<br><br>
Cry Classification System
<br>
The core of the research focuses on analyzing baby cry audio recordings from the Donate-A-Cry dataset.
To extract meaningful information, I used MFCC (Mel-Frequency Cepstral Coefficients), which is one of the most common techniques for representing human and infant vocal signals.
After extracting MFCC features with the Librosa library, I built a classification logic that predicts whether the baby is hungry, tired, uncomfortable, experiencing belly pain,
or needs to burp.

To make the system more accessible, I developed a small desktop application using Tkinter, where users can upload any audio file (.wav or .mp3) and immediately receive a classification result.
This simple interface demonstrates how machine learning and user interaction can be combined inside a real application.

<br><br>
Recommendation System & BLEU Score Evaluation
<br>

The second part of the research explores how recommendation systems work. For this, I applied my model to the MovieLens 20M dataset,
creating a simple content-based search engine that recommends similar items based on text and metadata similarity.
I then evaluated the quality of the recommendations using the BLEU score, 
a metric typically used in natural language processing to measure the similarity between predicted text and a reference sentence.

This section helped me understand how recommender systems are evaluated,
how similarity-based models work, and how metrics like BLEU can be used to validate AI-generated predictions.
The goal of this part was to build a foundation for integrating a personalized advice module into the baby assistant in the future.


<br><br>

The Baby Assistant research represents an early attempt at using AI to support childcare tasks.
Although still a prototype,
it demonstrates how technology can assist parents by analyzing sound patterns and generating meaningful recommendations based on both audio signals and learned behavior patterns.

<br><br>


Screenshots:
{% include figure image_path="/assets/images/BabyAssistant/apr1.png" caption="Samples classification" %}
{% include figure image_path="/assets/images/BabyAssistant/apr2.png" caption="Evaluation metrics" %}
{% include figure image_path="/assets/images/BabyAssistant/apr3.png" caption="Cry Classification" %}
{% include figure image_path="/assets/images/BabyAssistant/apr4.png" caption="Recommendation System" %}














