# Milestone II Project: Predicting Movie Genres

## Part A
- Tokenized the overview and lemmatized the text for each movie.
- Vectorized the overview by converting them to a matrix of TF-IDF features for each movie.
- Built multi-class classifiers including OneVsRestClassifier, DecisionTreeClassifier,
    KNeighborsClassifier and RandomForestClassifier, and evaluated their performance through metrics
    such as accuracy, hamming loss and etc.

## Part B
- Vectorized the keywords by converting them to a matrix of TF-IDF features for each movie.
- Clustered the vectorized keywords through K-means and determined the optimal number of clusters through cross validation.
- Visualized each keyword cluster by generating their word clouds.
