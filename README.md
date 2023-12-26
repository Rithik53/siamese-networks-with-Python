# siamese-networks-with-Python
Building image pairs for siamese networks with Python


When training siamese networks we need to have positive pairs and negative pairs:

Positive pairs: Two images that belong to the same class (ex., two images of the same person, two examples of the same signature, etc.)
Negative pairs: Two images that belong to different classes (ex., two images of different people, two examples of different signatures, etc.)

Siamese networks contain one or more identical networks, and those identical networks have the same parameters and weights. If the weights of one network update, the weights of the other network also update. They have to be identical. The final layer is usually an embedding layer that calculates the distance between the outputs.
