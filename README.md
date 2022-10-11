# Sentiment Analysis, Emotion Recognition and Hate Speech Detection on English tweets

Natural Language Processing tasks have been widely studied in the context of big corpora, but, when applied to social media content, they have been proven to be harder. This is mainly due to the following reasons:

- Social media have a high-paced, conversational and idiosyncratic nature;
- There might be restriction in the number of characters allowed (this is the case on Twitter);
- Short texts contains a limited amount of contextual cues;
- The lack of a unified evaluation framework makes it hard to compare different models.

In this project I am going to use BERTweet, a large-scale language model pretrained on English tweets, and I will evaluate its performances on three different NLP tasks:

- Emotion Recognition, which consists in recognizing the emotion evoked in a text (a tweet in this case);
- Hate Speech Detection, which consists in understanding whether a tweet is hateful or not towards certain target communities;
- Sentiment Analysis, i.e. the task of recognizing if the content of a text is positive, negative or neutral.