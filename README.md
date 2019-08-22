# un-trdiff
Exploration of the United Nations corpus and prediction of translation difficulty

## United Nations Corpus
![UN_Words_PerDay](img/un_words_per_day.png)    
**Figure 1.** Time it took to translate a document against the length of the document in words for a set of approximately 250 United Nations public documents.

![UN_Words_PerDay_Category](img/un_wpd_category.png)    
**Figure 2.** Distribution of translation rate (words per day) for a set of approximately 250 United Nations public documents.

![UN_TER_Histogram](img/un_ter_hist.png)    
**Figure 3.** Distribution of translation edit rate for machine translated sentences with human reference for UN documents after removal of top and bottom 5% of TER scores. Original documents in English translated to Spanish (left) and French (right). 

![UN_TER_PerSec](img/un_ter_wps.png)    
**Figure 4.** Correlation of TER of machine translated sentences versus words translated per second for human translation of the same sentences.