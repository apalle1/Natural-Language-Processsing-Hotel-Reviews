# Natural-Language-Processsing-Hotel-Reviews

**1. Sentiment Analysis and Aggregation**
* Compute average Vader sentiment and average ground truth rating per hotel.
* Rank hotels by
  * Average Ground Truth Sentiment
  * Average Vader Compound Sentiment Score
  * Show both top-5 and bottom-5 for both ranking methods. Do they agree or are there interesting differences?

**2. Frequency Analysis**
* Use term frequency of the words for (i) positive reviews and (ii) negative with ground truth
sentiment to rank the top-50 most frequent non-stopwords in the review collection. Do you
note anything interesting and/or locale-specific about these top-ranked words?
* Repeat this analysis for the top-50 noun phrases and note any interesting results.


**3. Mutual Information**

* Use mutual information (MI) with ground truth sentiment to rank the top-50 most sentiment-
bearing non-stopwords in the review collection. Do you note anything interesting and/or
locale-specific about these top-ranked words?
* Repeat this analysis for the top-50 noun phrases and note any interesting results.

**4. Pointwise Mutual Information**
* For ground truth sentiment, calculate the top-50 words according to PMI of the word occuring
with (i) positive reviews and (ii) negative reviews. Do you note anything interesting and/or
locale-specific about these top-ranked words?
* Repeat this analysis for the top-50 noun phrases and note any interesting results.
* Repeat this analysis for the single top and single bottom hotel (according to the ground
truth rating). Do you gain any useful hotel-specific insights about what is good and bad
about these two hotels? If not, explain why not.

**5. General Plots**
* Histogram
  * Show separate histograms of ground truth and Vader sentiment scores (ignore hotel ID).
Do you notice any interesting differences? 
  * Show a histogram of the number of reviews per hotel. Do you notice any interesting
trends? Are these expected?

* Boxplots
  * In two plots, one for ground truth star rating and one for Vader sentiment, show a plot
of 5 side-by-side boxplots of these scores.
  * Report the mean and variance of the ground truth and Vader sentiment scores for the
top-5 ranked hotels according to star rating.
  * Which do you find more informative, the boxplots or the mean and variance, or are they
equally informative? Why?

* Scatterplots and heatmaps
  * Show both a scatterplot and heatmap of ground truth score (star rating) versus Vader
sentiment score. Each review is a point on the scatterplot. Do you notice anything
interesting? What does this tell you about star ratings vs. Vader sentiment scores?
What does this tell you about human ratings and/or Vader sentiment analysis?
  * Show two scatterplots and two heatmaps of the length of reviews versus each of ground
truth score and Vader sentiment score. Each review is a point on the scatterplot. Are
there any trends?
  * Show two scatterplots of the number of reviews per hotel versus each of average ground
truth score and average Vader sentiment score. In this case, each hotel is a single point
on the scatterplot. Are there any trends?
