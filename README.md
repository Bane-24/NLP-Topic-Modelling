# Topic Modeling of State of the Union Speeches (1790–2012)

---

## Project Overview

The project applies Natural Language Processing (NLP) and topic modeling techniques to analyze U.S. State of the Union speeches from 1790–2012. The aim is to uncover evolving themes and align them with pivotal historical events, providing insights into the shifting priorities and concerns of U.S. leadership over time.

---

## Business Problem

Understanding historical shifts in political focus is crucial for studying governance trends, societal values, and policy evolution. The speeches represent decades of leadership priorities, offering a unique opportunity to identify recurring themes and their correlation with historical milestones.

---

## Machine Learning Goal

To develop an unsupervised topic modeling pipeline that extracts and identifies dominant themes from speeches across centuries, providing interpretable insights into historical and political discourse.

---

## Methodology

### Preprocessing
- Removed stopwords, punctuation, and irrelevant text.
- Lemmatization and stemming for word standardization.
- Created a dictionary and bag-of-words representation of the corpus.

### Topic Modeling Techniques
1. **TF-IDF Vectorization**: Transformed speeches into weighted document vectors.
2. **Latent Semantic Indexing (LSI)**: Leveraged linear algebraic methods to identify latent themes.
3. **Latent Dirichlet Allocation (LDA)**: Utilized probabilistic modeling to extract topics.

### Comparative Analysis
- Evaluated coherence scores to determine model quality.
- Annotated topics based on historical relevance.
- Conducted decade-wise summarization to trace thematic shifts over time.

---

## Toolkits Used

- **Python Libraries**: 
  - **NLP**: `nltk`, `spaCy`
  - **Modeling**: `gensim`, `sklearn`
  - **Visualization**: `matplotlib`, `wordcloud`
- **Data Processing**: `pandas`, `numpy`

---

## Results

- **LSI and LDA Performance**:
  - LDA outperformed LSI due to its probabilistic approach.
  - Coherence scores validated model quality and thematic clarity.

- **Key Findings**:
  - Identified dominant themes such as trade disputes, economic recovery, civil rights, and global crises.
  - Decade-wise summaries highlighted major historical trends like industrialization, war periods, and social reforms.

- **Visualizations**:
  - Word clouds provided intuitive representations of topics.
  - Decade-grouped topics offered insights into thematic evolution.

---

## Future Work

1. **Hyperparameter Tuning**: Optimize LDA for improved coherence and granularity.
2. **Modern Speeches**: Extend analysis to recent State of the Union addresses.
3. **Multi-modal Analysis**: Incorporate audio or video data for richer insights.
4. **Real-Time Applications**: Develop real-time topic extraction tools for political discourse.

---

## Conclusion

This project demonstrates the utility of NLP and topic modeling in extracting insights from historical texts. By leveraging LSI and LDA, it uncovers the evolving themes in political discourse, providing a framework for analyzing large corpora of political or historical data. Future iterations can enhance the granularity and extend the methodology to modern datasets.
