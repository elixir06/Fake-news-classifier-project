# Fake-news-classifier-project

## Context Background:

Over the years, U.S. politics has been heavily influenced by the spread of misinformation, especially on social media and online news platforms. Fake news has played a big role in shaping how people see political events and issues, often leading to confusion and distrust. With so much content out there, it’s becoming harder for people to tell what’s real and what’s fake. In today’s world of free speech, it’s more important than ever to have tools that help people sort fact from fiction in political news.

## Problem Statement:

The constant flow of political news online makes it tough to know what's accurate and what’s not. Over time, fake news has been used to steer public opinion and deepen political divides, creating a lot of mistrust. The challenge is to create a system that can reliably figure out whether a political news article is real or fake, just from its title or text. Existing methods for spotting fake news haven’t kept pace with the rapid spread of misinformation in the political landscape.

## Objective:

The goal is to develop a machine learning model that can accurately tell if a political news article is real or fake, using either the title or the full text. This project aims to help people become more aware of misinformation in U.S. politics, so they can make better-informed decisions. By building this tool, we hope to fight the spread of fake news and make sure political discussions are grounded in reliable, trustworthy information.


#### Conclusion

To conclude, it seems that the word "republican" and "said" are significantly used in real news compared with fake news. The chosen model (XGBoost) managed to achieve 92.5% accuracy in distinguishing real and fake news.

#### model limitation 

- the model was only trained from articles revolving around US politics, to be used more globally, further training with articles outside of US will be needed
- dataset context is politics, to predict articles outside this field might produce less accurate results.
