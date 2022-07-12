# ML_Text_classification

## Goal
Text classification based on the emotion that it represents. This is multiclassification problem.

## Data 
Data has two columns: Text (feature,X) and Emotions (target,y).<br>
 There are six classes of emotion included in the data : <br>
 `0: anger` <br>
 `1: fear` <br>
 `2: happy` <br>
 `3: love` <br>
 `4: sadness` <br> 
 `5: surprise`

## EDA

### Most common words

<img src="https://github.com/immayankprakash/ML_Text_classification/blob/master/images/most_common_word.png" height = '700' width= '700' >

### Sentiment analysis

<img src="https://github.com/immayankprakash/ML_Text_classification/blob/master/images/sentiment_analysis.png" height = '500' width= '700' >

### Class distribution 

<img src="https://github.com/immayankprakash/ML_Text_classification/blob/master/images/distribution.png" height = '400' width= '700'>

### Balanced class distribution (using SMOTE)

<img src="https://github.com/immayankprakash/ML_Text_classification/blob/master/images/balanced.png" height = '400' width= '700'>

## ML model
Multinomial Naive Bayes (MNB)

## Results

`Training set accuracy: 0.899`<br>
`Testing set accuracy: 0.822`<br>
`Testing set F1 score: 0.826` <br>
`Average accuracy after 5 fold cross validation : 0.79 +/- 0.04`<br>
`Average F1-score after 5 fold cross validation : 0.77 +/- 0.05`


### Confusion matrix

<img src="https://github.com/immayankprakash/ML_Text_classification/blob/master/images/confusion-matrix-MNB.png" >
