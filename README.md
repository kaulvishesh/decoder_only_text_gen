# **We Build GPT**

## **Overview**
This project involves building a GPT-like model using character-level processing on textual data. The primary goal is to create a neural network capable of generating text based on input sequences, leveraging PyTorch and GPU acceleration. The model implements essential components of transformer-based architectures in a simplified manner to generate coherent text outputs.

## **Features**
- Character-level text processing and vocabulary creation.
- Encoding and decoding of text into numerical representations for neural network processing.
- Implementation of neural network layers, including embedding layers and recurrent connections.
- GPU-accelerated model training and inference using PyTorch.
- Training loop with loss computation and backpropagation.
- Text generation from trained model using probabilistic sampling.

## **Data**
The project uses a text file, `the_office_dialogues.txt`, as the dataset. This dataset contains dialogues from "The Office" series. Preprocessing involves:
- Cleaning and tokenizing raw text.
- Building a character-level vocabulary.
- Encoding text into integer sequences for training.

## **Installation**
### Prerequisites
- Python 3.x
- PyTorch
- NumPy
- Pandas

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/kaulvishesh/we-build-gpt.git
   cd we-build-gpt
2. Place the the_office_dialogues.txt file in the project directory.
## **Usage**

Run the notebook cells sequentially to:

1. **Load and preprocess the dataset**:
   - Tokenize text into characters.
   - Build a mapping between characters and numerical indices.

2. **Build the model**, which includes:
   - Defining the embedding layer for character encoding.
   - Implementing recurrent or transformer-based layers for sequence processing.
   - Adding output layers for character prediction.

3. **Train the model** using:
   - Cross-entropy loss for character-level predictions.
   - Adam optimizer for gradient updates.
   - Dynamic learning rate adjustments for improved convergence.

4. **Generate text predictions** using the trained model, with optional temperature-based sampling for creative outputs.

## **Contributing**

Contributions are welcome! Please fork the repository and submit a pull request. Contributions can include:

- Improvements to the model architecture.
- Optimization of the training pipeline.
- Additional features, such as support for word-level processing.

## **License**

This project is licensed under the MIT License.
