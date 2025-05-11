# Master Thesis

## Machine learning method utilization for Lithuanian company clustering

### Abstract

Effective understanding and interpretability of the economic landscape of a country requires an identification of all business activities. When companies declare their activities, they are legally required to declare only their main activity, often omitting secondary operations. This limitation leads to an incomplete representation of the true economic realities. Lithuania utilized the NACE based economic activities classification system, which consists of six digits. The first four digits denote broad industry categories, while the remaining two digits provide a finer national-level classification. This paper aims to apply clustering methods for enterprise description in order to identify the economic activities of Lithuanian enterprises. The dataset used in this paper consists of 28 350 enterprise descriptions, sourced from the publicly available business directory "Rekvizitai.lt." The initial experiments showed that satisfactory clustering results can be achieved using LaBSE and Word2Vec embeddings in conjunction with K-means, Gaussian Mixture Model, Agglomerative clustering and Mean Shift. These results suggest that clustering techniques can be used on enterprise descriptions to capture patterns and segment them. To further refine the clustering results a hyperparameter search is planned to optimize model performance. 

```Keywords: Clustering, NACE, Enterprise Activities ```

## Project structure

1. `helpers` - contains helper scripts. At this point DEC script only.
2. `notebooks` - contains all workable notebooks with the experiments conducted during this research