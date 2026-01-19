# **Creating a word recommendation system while typing; for a technical individual using four distinct research papers**
This project uses 4 research domains: LLMs, Computer Vision, CyberSecurity, and Transformers to train the model using LSTM.
---

# WordForecast-LSTM: Contextual Next-Word Prediction

**WordForecast-LSTM** is a natural language processing (NLP) tool that leverages Recurrent Neural Networks (RNNs) to predict the most probable succeeding word in a sentence. The model is trained on a specialized corpus extracted from academic papers covering ChatGPT, Metaverse Computer Vision, Cyber Security, and Molecular Transformer technology.

##  Features

* **PDF Data Extraction:** Automated text mining from multiple research papers using `PyPDF2`.
* **Dynamic Tokenization:** Intelligent word-to-integer mapping using TensorFlow's Keras Tokenizer.
* **Sequential Modeling:** Implements a high-capacity **LSTM** architecture to capture long-term dependencies in technical text.
* **Zero-Padding Optimization:** Uses pre-padding sequences to ensure uniform input dimensions for varying sentence lengths.

##  Architecture

The model is built using a sequential deep learning pipeline:

1. **Embedding Layer:** Converts word indices into 100-dimensional dense vectors.
2. **LSTM Layer:** 400 units to process temporal sequences and context.
3. **Dense Layer:** A Softmax output layer mapping to the entire vocabulary size for multiclass probability distribution.

##  Dataset

The model extracts knowledge from five core domains:

* Generative AI (ChatGPT for Good)
* The Metaverse (Computer Vision)
* Cyber Security (Threats and Implications)
* Medical AI (LLMs in Medicine)
* Molecular Science (Transformer Technology)

##  Installation & Usage

### Prerequisites

```bash
pip install tensorflow numpy PyPDF2

```

### Running the Predictor

1. **Load the Script:** Ensure your PDF files are in the designated `/content/` or project directory.
2. **Train the Model:** The script will tokenize the text and run for 20 epochs.
3. **Inference:**
```python
text = "Computer"
# The model will predict the next technical word based on the training corpus

```



##  Model Performance

* **Optimizer:** Adam
* **Loss Function:** Categorical Crossentropy
* **Metrics:** Accuracy

---

**Disclaimer:** This project is intended for educational and research purposes in the field of Natural Language Processing.

Would you like me to refine the technical specifications or add a section on how to visualize the training loss?
