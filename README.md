# LDA Topic Modeling Project

This project demonstrates **Latent Dirichlet Allocation (LDA)** topic modeling on a text dataset using Python. The script preprocesses the data, trains an LDA model, and visualizes the topics with **pyLDAvis**.

## Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/sydubaid/lda-topic-modeling.git
cd lda-topic-modeling
pip install -r requirements.txt

Usage
Place your JSON dataset in the project folder.
Run the script:
python lda_model.py
The script will preprocess the text, train the LDA model, and generate an interactive topic visualization saved as lda_visualization.html.

Dependencies
nltk: Text preprocessing
gensim: LDA model
pyLDAvis: Topic visualization
