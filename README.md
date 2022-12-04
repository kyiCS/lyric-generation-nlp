# lyric-generation-nlp
- Dawson Sargent, Chenghui Song, Kelvin Yi
<br>

## Aim: Generate artificial text to mimic song lyrics. 
<br>

#### Dataset:
#### 2 csv files (lyrics-data.csv and artists-data.csvfrom) from:
https://www.kaggle.com/datasets/neisse/scrapped-lyrics-from-6-genres?select=lyrics-data.csv

#### Models for Lyric Generation:
- Cell-based RNN (Chenghui)
- LSTM with Markov chains (Chenghui)
- GPT-2 (Dawson)

#### Models for Lyric Classification:
- Logistic Regression, Decision Tree, Random Forest, SVC (Kelvin)

### Model evaluation: 
- BERTScore (Kelvin)
- BLEURT (Kelvin)


## Runing Instructions
- Find the models in Jupyter notebook files staring with "models_". 
- Download all the necessary datasets from kaggle and the repository.
- Download the dependencies and imports listed in the files.
- Run the Jupyter notebook.


### references:
- Create Your Own Artificial Shakespeare in 10 Minutes with Natural Language Processing <br>
https://towardsdatascience.com/create-your-own-artificial-shakespeare-in-10-minutes-with-natural-language-processing-1fde5edc8f28

- Poetry Generator (RNN Markov)<br>
https://www.kaggle.com/code/paultimothymooney/poetry-generator-rnn-markov

- GPT-2 Model card <br>
https://huggingface.co/gpt2

- Text generation with GPT-2<br>
https://www.modeldifferently.com/en/2021/12/generaci%C3%B3n-de-fake-news-con-gpt-2/

- A Gentle Introduction to Calculating the BLEU Score for Text in Python <br>
https://machinelearningmastery.com/calculate-bleu-score-for-text-python/ 

- How to calculate BLEU Score in Python?<br>
https://www.digitalocean.com/community/tutorials/bleu-score-in-python 

- Metric: bert_score<br>
https://huggingface.co/spaces/evaluate-metric/bertscore

- BLEURT: a Transfer Learning-Based Metric for Natural Language Generation<br>
https://github.com/google-research/bleurt 
