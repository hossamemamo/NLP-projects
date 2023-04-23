# Arabic-Egyptian Word2Vec

This repository contains an implementation of the word2vec model using Arabic-Egyptian Wikipedia data. The aim is to replicate the methods outlined in the original word2vec paper for Arabic language.

## Progress

- [x] Implemented skip-gram model
- [ ] Implemented CBOW model (in progress)
- [ ] Cleaned up notebook
- [ ] Try better dataset for the task
- [ ] better optimize the code and don't load all the data into the ram
## Usage

To use the implementation, simply clone the repository and run the provided Jupyter notebook. The notebook contains the implementation of the skip-gram model and demonstrates how to train and evaluate the model using the Arabic-Egyptian Wikipedia data.

## Dependencies

The implementation relies on the following dependencies:

- Python 3.6 or higher
- PyTorch
- NumPy
- Pandas
- Jupyter Notebook

## Acknowledgments

- The word2vec paper by Tomas Mikolov et al. (2013) for providing the inspiration and foundation for this project.
- The Arabic-Egyptian comparable Wikipedia corpus provided by [M. Saad](https://www.kaggle.com/datasets/mksaad/arb-egy-cmp-corpus) on Kaggle for providing the data used in this project.
- Stanford's CS224N: Natural Language Processing with Deep Learning course, taught by Christopher Manning and Abigail See, for providing valuable insights and knowledge on natural language processing. Check out the course playlist [here](https://www.youtube.com/playlist?list=PLoROMvodv4rOSH4v6133s9LFPRHjEmbmJ).
