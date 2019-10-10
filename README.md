<h1> Restricted-Boltzmann-Machines</h1>
Building the movie recommender system using RBM

<h2>Boltzmann Machine</h2>
Boltzmann machine is a network of symmetrically connected nodes which makes stochastic decision, to be turned on or off. It is an unsupervised machine learning algorithm which helps to discover latent features present in the dataset. 

<h2>Restricted Boltzmann Machine</h2>
Restricted Boltzmann Machine are shallow neural nets that learn to reconstruct data by themselves in an unsupervised fashion. They belong to energy based models. They can be used for dimensionality reduction, classification, regression, collaborative filtering, feature learning ,topic modeling and even Deep Belief Networks.

<h2>How it works?</h2>
It is a 2 layered network. IN an RBM, we have a symmetric bipartite graph where no two units within the same group are connected. Simply, RBM takes the inputs and translate those into a set of binary values that represent them in the hidden layer. Then these, numbers can be translated back to reconstruct the inputs. Through several forward and backward passes, the RBM will be trained, and a trained RBM can reveal which features are the most important ones when detecting patterns.