
### My JSC370 Final Project Website

Link to the website: https://lynnqian.github.io/JSC370_final_project/

You can find the report here: https://github.com/lynnqian/JSC370_final_project/blob/master/JSC%20Final%20files%20/JSC_final.pdf

#### Introduction

Nowadays, we have so many apps on our phone and computers and everyone’s life is associated with them. I want to know people’s opinion on different apps and whether they favor some apps with particular characteristics than others. I have narrowed my target to apps on Google Play Store.

#### Primary question of interest

The primary question of interest is: What are the factors for different app’s rating?

This question can be decomposed into smaller questions:

* What is the association between number of reviews and rating of the app?
* What is the association between number of installs and the rating of the app?
* What is the association between the category of the app and the rating of the app?
* What is the association between the size of the app and the rating of the app?

#### Variables we are interested in

- `Rating`: the rating of the app. We want to find all the factors affecting the rating.
- `Reviews`: the number of reviews of the app. Could indicate the popularity of the app.
- `Category`: the category of the app. Examples are: `art and design`, `Game`, `Tools`, etc.
- `Size`: the size of the app. This is a new variable compared with my midterm project, and we will discuss about it below.
- `Installs`: number of installs of the app.


#### Conclusion

In conclusion, we found that the `Rating` of apps on Google Play Store indeed depends on many other factors, and through our analysis, we found that number of `Installs` of the app, number of `Reviews` of the app, `Category` of the app and `Size` of the app all contributes to the variation of `Rating`, with `Size` contributes less than other three predictors. The relationship between predictors and response is non-linear, there are associations and interactions between the four predictors stated above, and the non-linear association model with cubic regression splines we generated could explain 13.5% of the deviance in `Rating`. We also built a regression tree, which aligns with our hypothesis and confirmed the positive relationship between number of `Reviews` and `Rating`.
