# Chainbreakers
SAMHAR COVID-19 Hackathon

We are developing an interactive solution to assist health professional to get speedy, accurate and latest insights from huge amount of COVID-19 literatures.

Given the large number of literature and the rapid spread of COVID-19, it is difficult for health professionals to keep up with new information on the virus. There are more than 44000 research articles already published and its growing. This is a very big challenge for a health care professional to get the speedy and accurate information from all the literature available in the world.  

In addition, there is a need for getting the insight quickly, which can accelerate the COVID-19 vaccination research. Our solution to provide speedy, accurate & latest information via a context aware Chat-bot which will do the data mining from given articles based on Abstract, Author, Publication, Vital keywords etc. The heart of the system will be a clustering algorithm, which would do the cluster of 44000 articles based on the key words and other user inputs. User interaction will be through context aware Deep NLP chat-bot, which would provide the generic information about corona/COVID-19 information (preventive measures, helpline, medical facilities etc) and article search for relevant topics. Also chat-bot can auto summarize the articles based on user demand, this will enhance the experience of health professional to get the summary of the literature quickly.

 

 Approach:
Parse the text from the body of each document using Natural Language Processing (NLP).
Turn each document instance  di  into a feature vector  Xi  using Term Frequency–inverse Document Frequency (TF-IDF).
Apply Dimensionality Reduction to each feature vector  Xi  using t-Distributed Stochastic Neighbor Embedding (t-SNE) to cluster similar research articles in the two dimensional plane  X  embedding  Y1 .
Use Principal Component Analysis (PCA) to project down the dimensions of  X  to a number of dimensions that will keep .95 variance while removing noise and outliers in embedding  Y2 .
Apply k-means clustering on  Y2 , where  k  is 20, to label each cluster on  Y1 .
Apply Topic Modeling on  X  using Latent Dirichlet Allocation (LDA) to discover keywords from each cluster.
Investigate the clusters visually on the plot, zooming down to specific articles as needed, and via classification using Stochastic Gradient Descent (SGD).