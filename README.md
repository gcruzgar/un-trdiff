# un-trdiff
Exploration of the United Nations corpus and prediction of translation difficulty

## Things to cover

- Descriptive statistics of data
- Histograms + mean and medain values
- Correlation of sentence length and time taken to translate
- Show 2 or 3 easy and difficult sentence examples for en-fr and en-es
- Prediction experiments:
    + Biber - time per document
    + Biber - TER
    + XLM - TER
    + TER - time per sentence

## United Nations Corpus
![UN_Words_PerDay](img/un_words_per_day.png)    
**Figure 1.** Time it took to translate a document against the length of the document in words for a set of approximately 250 United Nations public documents.

![UN_Words_PerDay_Category](img/un_wpd_category.png)    
**Figure 2.** Distribution of translation rate (words per day) for a set of approximately 250 United Nations public documents.

![UN_TER_Histogram](img/un_ter_hist.png)    
**Figure 3.** Distribution of translation edit rate for machine translated sentences with human reference for UN documents after removal of top and bottom 5% of TER scores. Original documents in English translated to Spanish (left) and French (right). 

![UN_TER_PerSec](img/un_ter_wps.png)    
**Figure 4.** Correlation of TER of machine translated sentences versus words translated per second for human translation of the same sentences.

![Fr_Timed_Sentences_Time_Words](img/french_time_words.png)    
**Figure 5.** Time taken to translate a sentence against the number of words in the sentence.
