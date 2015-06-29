# Sentiment-Analysis
This is a humble attempt to have create a basic sentiment analysis code using python
Some information I have got after some googling.
	People are doing sentiment analysis in two ways.  (I have concentrated by searches only using python. Not Java)
	
1)	Lexicon based approaches

  The basic idea is, use each term and try to understand its sentiment (polarity) whether it is positive or negative

    For eg: Excellent – positive
    Bad - negative

  Some words can be highly or merely positive / negative. So each word will have polarity score (assume between -1  to 1)  High positive words will have high +ve scores (close to 1) high negative sentiment words will have high negative scores (close to -1). To understand the sentence / document level sentiment, we will add the scores of each word and Final score it will determined

2)	Supervised Learning approach

