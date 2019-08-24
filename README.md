# Emotional Dictionary For Sentiment Analysis

The base of this project will be built off of the work done by Yanghui Rao (City University of Hong Kong), Wenyin Liu (GuangDong University of Technology), Qing Li (City University of Hong Kong), and Mingliang Chen (City University of Hong Kong) from their article **Building emotional dictionary for sentiment analysis of online news** published April 2013, you will find a pdf of this paper in the repo. Below will be the abstract from the paper to give you an idea of what the paper involves.

**Abstract** Sentiment analysis of online documents such as news articles, blogs and microblogs has received increasing attention in recent years. In this article, we propose an efficient algorithm and three pruning strategies to automatically build a word-level emo- tional dictionary for social emotion detection. In the dictionary, each word is associated with the distribution on a series of human emotions. In addition, a method based on topic modeling is proposed to construct a topic-level dictionary, where each topic is correlated with social emotions. Experiment on the real-world data sets has validated the effectiveness and reliability of the methods. Compared with other lexicons, the dictionary generated using our approach is language-independent, fine-grained, and volume-unlimited. The generated dictionary has a wide range of applications, including predicting the emotional distribution of news articles, identifying social emotions on certain entities and news events.

I will be showing all of the steps that I will need to go through to understand this paper and how to turn the sigma and mathematical notation into code for productino use. My aim is for anyone reading this to get a full grasp on how this process works so that if any improvements can be made it will be easy to find where the improvement should be implemented.

First, note for this article is that this was orignially based on mandarin chinese text data and the emotions that are displayed may seem a little odd for a western audience. Another goal of this project is to gain an indepth understanding of the method so that we can apply it to any emotion that we so choose. The emotions beings measured, in the paper, are as follows: touching, empathy, boredom, anger, amusement, sadness, surprise, warmness.

Second, a good understanding of discrete mathematics(DM) and Bayesian Statistics is necessary to understand this paper. I will provide relative information on this subject which is needed to understand this project.

Third, it is important for me to note that this is the first time I am doing most of these things and as such any comments on how to improve this process, the code, or the explanations would be greatly appreciated.

