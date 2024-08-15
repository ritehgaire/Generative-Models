*** Transformer

This project focuses on building and training a custom GPT model using Transformer architecture. 

The process begins by passing input text through token and position embedding layers, which encode the text into a format suitable for the Transformer. 

The encoded input then flows through a series of Transformer blocks, which are responsible for capturing complex patterns and relationships within the data. 

Finally, the network outputs predictions through a Dense layer with softmax activation, generating a probability distribution over the entire vocabulary. 

This setup allows for powerful text generation, making it possible to produce coherent and contextually relevant sequences based on the input text.


*** Variational Autoencoder (VAE)

The Variational Autoencoder (VAE) component of this project is designed for image generation. 

During training, the autoencoder learns to map input images into a latent space, where similar-looking items naturally cluster together, even without explicit labels. 

This clustering occurs because the VAE encodes the visual features of the images into a compact representation. 

Once trained, the model can generate new images by sampling points from this latent space, effectively creating novel items that resemble the input data. 

This ability to explore the latent space and generate new instances highlights the VAE’s strength in unsupervised learning and its application in creative and generative tasks.
