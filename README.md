# t-SNE-on-Game-of-Thrones
t-SNE visualization 

t-Distributed Stochastic Neighbor Embedding (t-SNE) is an unsupervised, non-linear technique primarily used for data exploration and visualizing high-dimensional data.
In simpler terms, t-SNE gives you a feel or intuition of how the data is arranged in a high-dimensional space. 

Steps to do t-SNE on any dataset

1.Load the dataset

2.Preprocessing methods
 missing values
 Encoding to categorical
 
3.Remove unwanted variable 

4.Feature scaling

5.apply t-SNE and extract new components

from sklearn.manifold import TSNE
t_sne=TSNE(n_components=2,random_state=0)

->-> n_components is the no of features obtained after t-SNE
and join the new components with the orignal data

6.Plot the new components



Thank you
