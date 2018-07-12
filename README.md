#CDAP research project at SLIIT

# spacy-summary
A test summarizer that uses [spacy.io](https://spacy.io/).

## Usage
To get started, install the dependencies:

```bash
# Using virtualenv
virtualenv .env
source .env/bin/activate

# Install python libraries
pip install -r requirements.txt
python -m spacy download en
python --version = 2.7
```

The program takes the text file to summarize and the number of sentences to include in the summary:
# Reads and summarizes document.txt in 3 sentences
python main.py test.txt 3

# Steps for execute the program
cd /CDAP ``` #navigate to root folder using conda terminal ```
conda activate py27 ``` #if the current python version 2.7 in conda terminal, then ignore this step ```
python main.py test.txt 3 ``` #no of output sentence in summary depends on the last argument value ```
