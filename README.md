<img src="https://github.com/axiom2018/700KYelpReviews/blob/main/700k_Yelp_Reviews.png"/>

## Description
<p align="left">
This is a text multiclassification dataset that is much more massive than normal ones. Link <a href="https://pytorch.org/text/stable/datasets.html#yelpreviewfull">here</a>.
Believe it or not I paused finishing the project in order to understand <a href="https://optuna.org/">Optuna</a> (a hyperparameter tuning library) and ended up doing an
entirely different project <a href=https://github.com/axiom2018/AG-News-Classification/tree/main/>here</a>, <b>JUST</b> so I can apply Optuna to <b>THIS</b> project. A bit
strange most definitely but if you're reading this you're clearly interested in the results. As with my other projects, the code is HEAVILY commented. Below is the project 
breakdown or what I've done in it:

  1) Exploratory Data Analysis
  2) Preprocessing
     - Using Regex, & PyTorch 
  3) Splitting
  4) Tokenization
  5) Building the vocabulary
  6) Padding
  7) Changing labels
  8) Dataset & Dataloaders
  9) Model Building
  10) Training & Validation functions
      - Seeing overfitting in validation training.
  11) Regularization understanding/explanations
      - What <b>is</b> regularization?
      - What <b>is</b> overfitting?
      - What <b>is</b> bias & variance?
      - Causes of variance
      - Regularization techniques such as L1/L2
      - Why L1 was selected and not L2
      - Importance of the lambda value.
  12) Optuna
      - Range for the lambda value and why it matters.
  13) Conclusion Notes & Realization

This project was most definitely tricky due to the large dataset causing training to go on for ages and even project <b>completion</b>. But I've learned and grown a lot
from it and I hope the reader can as well.
    


</p>
