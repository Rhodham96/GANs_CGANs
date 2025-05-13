# GANs and CGANs on MNIST Dataset

This repository contains Jupyter Notebooks that implement Generative Adversarial Networks (GANs) and Conditional Generative Adversarial Networks (CGANs) for generating handwritten digits from the MNIST dataset.

### Project Overview

* **GANs:** Implementation of a basic GAN to generate handwritten digits.

* **CGANs:** Implementation of a CGAN, which allows for generating specific digits by conditioning on labels.

### Goal

The goal of this project is to:

* Provide a practical understanding of GANs and CGANs.

* Demonstrate how CGANs can improve the controllability of the generation process.

* Offer a starting point for experimenting with GANs on image datasets.

### Repository Structure

* `notebooks/`: Contains the Jupyter Notebooks.

    * `GANs_MNIST.ipynb`: Implementation of a basic GAN for MNIST.

    * `CGANs_MNIST.ipynb`: Implementation of a CGAN for MNIST.

* `README.md`: This file.

### Requirements

To run the notebooks, you will need:

* Python 3

* PyTorch

* torchvision

* matplotlib

* Jupyter Notebook

You can install the required packages using pip:
```python
  pip install torch torchvision matplotlib jupyter
```

### Usage

1.  Clone this repository:

    ```
    git clone [https://github.com/your_username/your_repository_name.git](https://github.com/your_username/your_repository_name.git)
    ```

2.  Navigate to the repository directory:

    ```
    cd your_repository_name
    ```

3.  Navigate to the notebooks directory:

    ```
    cd notebooks
    ```

4.  Run the Jupyter Notebook:

    ```
    jupyter notebook
    ```

5.  Open the desired notebook (`GANs_MNIST.ipynb` or `CGANs_MNIST.ipynb`) and follow the instructions.

### Notebooks Description

* **GANs\_MNIST.ipynb:**

    * Implements a basic GAN with a Generator and Discriminator network.

    * Generates handwritten digits from random noise.

    * Visualizes the generated images during training.

    * Plots the Generator and Discriminator losses.

* **CGANs\_MNIST.ipynb:**

    * Implements a CGAN that takes labels as input to generate specific digits.

    * Demonstrates how to control the digit generation process.

    * Visualizes the generated images for different labels.

    * Plots of Generator and Discriminator losses.

### Results

The notebooks provide a step-by-step implementation of GANs and CGANs, along with visualizations of the generated images and training progress. Key results include:

* Comparison of image quality between basic GANs and CGANs.

* Demonstration of how CGANs can generate specific digits on demand.

* Plots of Generator and Discriminator losses during training.

### Contributing

Feel free to contribute to this project by submitting pull requests. You can:

* Improve the code.

* Add more visualizations.

* Implement advanced GAN techniques.

* Add more comments.

### Author

Robin Hamers ([Rhodham96](https://github.com/Rhodham96))

You can find more details about this project in [my article on Medium](https://medium.com/@robin.hamers) and connect with me on [LinkedIn](https://www.linkedin.com/in/robin-hamers/).

### License

This project is licensed under the MIT License.
