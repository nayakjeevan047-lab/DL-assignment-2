deep-learning-assignment
Install dependencies:

pip install torch torchvision tensorflow matplotlib seaborn scikit-learn
Open the notebook:

jupyter notebook
Run all cells in order.

Results
CNN Performance
Model	Test Accuracy
Custom CNN	92.05%
ResNet18	67.29%
RNN Model Comparison
Model	Test Accuracy
Simple RNN	81.12%
LSTM	85.21%
GRU	86.81%
GAN
The GAN successfully learned the distribution of Fashion-MNIST images and produced synthetic clothing samples.
Training stability was observed when discriminator accuracy stabilized near 50%, indicating balanced adversarial learning.

Generated Samples
Example GAN generated images:

GAN Samples

Key Observations
The custom CNN performed significantly better than the pretrained ResNet18 model on Fashion-MNIST.
LSTM and GRU outperformed the vanilla RNN in sentiment classification tasks.
The GAN successfully captured the general structure of Fashion-MNIST images, generating recognizable clothing patterns.
Author
Jeevan Krishna 
Information Science and Engineering
NMAM Institute of Technology

License
This project is intended for academic and educational purposes.
