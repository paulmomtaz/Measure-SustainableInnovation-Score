# Measuring Sustainable Innovation Using Machine Learning

## Requirement
The codes tested on Python 3.9.7 (Anaconda).

## Data
The raw data is a csv file including all articles with the topic of Sustainable Innovation gathered from Financial Times.

## Expanding the dictionary

1. This procedure follows [GitHub repository.](https://github.com/MS20190155/Measuring-Corporate-Culture-Using-Machine-Learning). Note that we upgrade their stanfordnlp package to stanza package.

2. Put the csv file containing all articles in the `/data/input/` path.

3. Adjust the python file `global_options.py` for your machine's hardware. The seed word list contains all key word search terms in the csv file.

4. Run the Jupyter Notebook `run.ipynb` .

5. Finally, the word-list will appear in the `outputs/dict/expanded_dict.csv` 


## SustainableInnovation score calculator

1. This procedure follows [GitHub repository.](https://github.com/sasi2400/sustainableentrepreneurship.org)

2. Replace the text in `SustainableInnovation_Score_Calculator.ipynb` and run the Jupyter Notebook, the SustainableInnovation Score of the text will be calculated and a word cloud will be drawn.