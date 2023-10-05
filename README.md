# Graph Convolutional Neural Networks for Knowledge-Graphs
1. Using GraphZoo (PyTorch based Graph Convolutional Neural Network toolkit) for Node Classification on CORA Dataset
2. The CORA dataset consists of about 2700 scientific publications belonging to one of 7 classes. Each feature (node in the graph) is in the form of one hot word vectors representing the presence or absence of the corresponding words from the dictionary with around 1500 words
3. The edges represent the relationship between the nodes, which are the citations between them
4. label_dict = {
    0: "Theory",
    1: "Reinforcement_Learning",
    2: "Genetic_Algorithms",
    3: "Neural_Networks",
    4: "Probabilistic_Methods",
    5: "Case_Based",
    6: "Rule_Learning"}

5. Futher Work: Testing performance of Hyperbolic Embeddings in GraphZoo ('Hyperboloid' and 'PoincareBall') to model hierarchical representations of tree-like datasets, such as WordNet
