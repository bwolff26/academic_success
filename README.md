# academic_success
From Kaggle's Playground:S4E6. They've been synthesizing their data, with the original's data dictionary found below.

## Introduction

Unlike previous ones, I'm going all out for this one. Thankfully, I am quite interested in this topic and have plenty of features to play with.

Might as well aim to do all sorts of unsupervised learning as well, make visualisations (and learn how to spell that word), etc. Coding wise I'm quite adept in my opinion (at least considering the meager amount of time I've befriended the Python), however when it comes to knowing packages, 'current data science news', and visualizationn there's still what to improve... So, let's do it (6/18/24)!

## Results

After basic cleaning (which we still attempted to do, not relying on Kaggle to let that one slide) and eda we made various observations (see ceda_i and visualizations_i for detail) on the nature of the data given.

To simplify our modeling, we decided to drop a number of columns that only were relevant to a negligible amount of records that anyways didn' seem to affect final results. Ultimately, a XGBoost model was selected that was trained on 80% of the 76kish student, leaving us with 20% for testing and the witheld 'validation/test' data of 51kish students. With a testing accuracy of .833 and a final validation accuracy of .834 it would seem that the model did well relative to the effort that was put into it (perhaps a mere hour testing various parameters of XGBoost, which did far better than the several other methods that were tried).

Now, from an interpretability standpoint I would likely never use a XGBoost, however for the sake of this competition where that factor doesn't matter then it is what it is. Pragmatically, I was pleased with the final result of .834 - being only .006ish off the highest scoring competitor. However, out of roughly 3k applicants this would only give us a median score. Ie, with this incredibly left-skewed distribution we did poor from an academic point of view. Thankfully, not all hope is lost: Besides entering this for the sake of giving me more opportunities to code, try new packages and techniques (finally tried XGBoost), and have data I feel like making visuals for, I have the most important thing: A project I feel like talking about, sharing my thoughts and the like to the public. Ie yes, academically there is much I can do to improve on every front. Yet, when I'm just trying to build up a portfolio to land that first data science job (7/3/24)... I'd hope this is yet another example to show my potential to future colleagues and employers.

### Sources

Original: https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success