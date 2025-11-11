## Santiago Zubieta
#### 2025

## 5-Day Gen AI Intensive Course
These notebooks are from the intensive GenAI course provided by [Kaggle](https://www.kaggle.com/discussions/general/545082). All steps on these notebooks were ran locally on my machine, with slight modifications to make them work outside of the Kaggle environment.

### Day_01
On the first day the following things are explored:
- Sending simple prompts
- Creating conversations
- Explore parameters like temperature and top_p
- Zero shot, one shot, and few shot prompting
- Chain of thought in models
- Reason and act
- Thinking mode in models
- Prompting to generate or explain code
- Code execution

### Day_02
On the second day the following things are explored:

#### Document Q&A with RAG
- Storing documents embeddings in ChromaDB
- Querying the vector database
- Simplify response document contents

#### Exploring text similarity with embeddings
- Calculare similarity scores with semantic similarity
- Visualize similarities of all documents in a heatmap
- See the ranking of similarities for a given entry

#### Build a neural classification network with Keras using embeddings
- Finding an appropriate dataset (e.g. 20 newsgroups text dataset)
- Prepare and sample a dataframe with some desired categories using Pandas
- Use tqdm for creating a progress bar when creating a compute intensive dataframe (e.g. creating embeddings)
- Use Keras to create a classifier model to train with the embeddings and the corresponding category mappings
- Predict a certain text category by using its embeddings with the embeddings trained model


