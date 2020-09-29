# START_HERE_START_HERE

1. Repo corresponding to published paper on ACM.
    
    **Idea:** Reorganize features of non-image data to introduce image-like feature structure. Also contains code for entropy measurement to estimate presence of local structures.
    
    **Dataset:** ISOLET. Contains sororant features.

    **Technologies/ Packages:**: PyTorch, NumPy, Pandas, Scipy, SKLearn
    **Concepts:** Deep Learning, CNN, ConvNet, t-SNE, Data Engineering, Feature Engineering, Model Tuning, Dimensionality Reduction, Feature Transformation
    
    **Link to repo:** https://github.com/tgh499/isolet_1D_convolution_updated

2.  Same feature embedding mthod. But with the text based 20Newsgroups dataset. Instead of tf-idf representation, a novel word-embedding (GloVe) based method was introduced and used.

    **Dataset:** 20Newsgroups. Transformed using 300D GloVe vectors generated from Wikipedia.

    **Link to repo:** https://github.com/tgh499/20_newsgroups_1d_convolution

3. Contextualized Spelling correction. 

    **Idea:** catching general typing mistakes is not that challenging. But correcting, ***there days*** to ***these days*** is much harder. There are no spelling mistakes here, but we know "there days" is how we speak. This project aims at solving this problem by intelligently gathering information from context.

    **Link to repo:** https://github.com/tgh499/contextualSpellingCorrection

4. AI game to create word chain

    Idea: Create word-chain from a given start-word to a given end-word. Constraint is that when creating the chain, only one character can change at a time.

    **Link to repo:** https://github.com/tgh499/wordChain_w_shrink_expand

5. Sentimient Analysis from Scratch

    **Idea:** Learn from 1.6 million tweets. Perform sentiment analysis on new text.

    **Accomplishments:** Best performing model in a graduate class.

    **Link to repo:** https://github.com/tgh499/sentiment_analysis/blob/master/sentiment_analysis.py