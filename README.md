# N-Gram Language Model

This code builds an N-gram language model based on a text corpus and generates random sentences using the model. Specifically, it reads in a text file called 'aa1.txt' and tokenizes it using the NLTK library. It then builds N-gram models for N=2 to N=6 and stores them in a dictionary called 'ngram_models', where the keys are the values of N and the values are lists of N-grams. The code also generates a list of trigrams (N=3) and computes their frequency distribution using the Python 'collections' module. It then writes the 10 most frequent trigrams to a file called 'frequent.txt'.

## Requirements

- Python 3.x
- NLTK
- collections

## Usage

1. Install the required packages by running `!pip install --user -U nltk` in a Python shell or terminal.
2. Download the NLTK tokenizers by running `nltk.download('punkt')`.
3. Download the KSUCCA Arabic Corpus from https://sourceforge.net/projects/ksucca-corpus/files/KSUCCA%20Files/ and save it as a plain text file with the name 'aa1.txt'
4. Replace the file name 'aa1.txt' in the code with the name of your corpus file if necessary.
5. Run the code in a Python shell or terminal. The code will generate a file called 'frequent.txt' that contains the 10 most frequent trigrams in the corpus and prompt you to enter the number of words and start word for 10 test sentences.
6. Use the 'generate_sentence' function in your own code by importing it from this script and calling it with the desired arguments.

## Resources

- [NLTK documentation](https://www.nltk.org/) - The official documentation for the Natural Language Toolkit (NLTK) library used in this code.
- [Python collections module documentation](https://docs.python.org/3/library/collections.html) - The official documentation for the collections module used in this code.
- [KSUCCA Arabic Corpus](https://sourceforge.net/projects/ksucca-corpus/files/KSUCCA%20Files/) - The source of the Arabic text corpus used in this code.
