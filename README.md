1. Playing with Tensors and dimensions
2. Linear Regression AutoGrad - maths
	1. Compute prediction
	2. Compute gradient
	3. Update weights
3. Linear Regression with Pytorch Autograd
	1. Prediction, gradient and weights with Pytorch
4. Model Loss and Optimizer
	1. Mean Squared Error
	2. Stochastic Gradient Descent
5. First Neural Network - MNIST
	1. Dataloader download
	2. Plot images
	3. NN architecture
	4. Resize tensors
	5. Training and validation scores
6. Softmax vs Cross Entropy Loss
	1. LogSoftMax
	2. NLLLoss (Negative Log likelihood loss)
7. CNN
	1. PIL transform
	2. CIFAR10 dataset vs MNIST dataset
	3. Plot images
	4. CNN architecture - 2 ways
	5. Training and evaluation
8. CNN - test
	1. Image shapes, tensor sizes for each layer in CNN architecture
	2. MaxPool
	3. CNN layer
9. CNN - classification
	1. Created my own functions for testing CNN on new images
10. Model Evaluation
	1. Fashion MNIST - FCNN
11. WebBaseLoader - LangChain
	1. Classify Newspaper articles - content, URL, date
12. Gradio HuggingFace
	1. Connect to Mistral and FLUX using gradio client


# 🧠 Deep Learning with PyTorch – Learning Journey

This collection of notebooks is organized to show my progress from foundational concepts to advanced applications. Click the badges to open them in Google Colab.

## 📚 Notebooks

| Module / Topic                  | Notebook Title                                      | Description                                                                 | Run Online |
|-------------------------------|------------------------------------------------------|-----------------------------------------------------------------------------|------------|
| **1. Foundations**            | Playing with Tensors and Dimensions                 | Introduction to PyTorch tensors, dimensionality, and tensor operations.    | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Adhira-Deogade/pytorch-learnings/blob/main/pytorch_tutorial_tensors.ipynb) |
| **2. Linear Regression**      | Linear Regression AutoGrad - Math Breakdown         | Manual implementation of linear regression with gradient computation and weight updates. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Adhira-Deogade/pytorch-learnings/blob/main/linear_regression_autograd.ipynb) |
|                               | Linear Regression with PyTorch Autograd             | Using PyTorch's autograd for prediction, gradients, and weight updates.    | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Adhira-Deogade/pytorch-learnings/blob/main/pytroch_autograd.ipynb) |
| **3. Optimization**           | Model Loss and Optimizer                            | Exploring MSE loss and SGD optimization in PyTorch.                         | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Adhira-Deogade/pytorch-learnings/blob/main/model_loss_optimizer.ipynb) |
| **4. Neural Networks**        | First Neural Network - MNIST                        | Full pipeline: loading MNIST, preprocessing, defining NN, and training.    | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Adhira-Deogade/pytorch-learnings/blob/main/first_neural_net.ipynb) |
| **5. Loss Functions**         | Softmax vs Cross Entropy Loss                       | Deep dive into LogSoftMax and Negative Log Likelihood loss.                | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Adhira-Deogade/pytorch-learnings/blob/main/softmax_and_cross_entropy_loss.ipynb) |
| **6. Convolutional Nets**     | CNN - CIFAR10 vs MNIST                              | Comparison of datasets, CNN architectures, and training pipeline.          | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
|                               | CNN - Test                                          | Analyze CNN layers, tensor sizes, MaxPooling, and architecture components. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
|                               | CNN - Classification on Custom Images               | Custom testing functions for classifying new images using trained CNN.     | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| **7. Evaluation**             | Model Evaluation - Fashion MNIST                    | Evaluate a fully connected NN on the Fashion MNIST dataset.                | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| **8. LangChain Integration**  | WebBaseLoader - Classify News Articles              | Use LangChain’s WebBaseLoader to classify articles by content, date, and URL. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |
| **9. UI & Deployment**        | Gradio + HuggingFace Integration                    | Create interactive web demos for models using Gradio and HuggingFace.      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)]() |

---
