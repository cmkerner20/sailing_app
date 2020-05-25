Developing an Algorithm that classifies sections of sailing boat tracks. 


NextSteps
1. Understand the data
    1. we probably haeve to set-up a AWS environment - how much will it cost? 
2. Try some more simple models - unnerstand how good we are guessing movements on same data - probably design some tool to help debug - some sort of graph which shows green points as guessed correctly etc - are there any out of box rnn models? instead of building pytorch? or is the use case too specific?
2. Do this tutorial - https://pytorch.org/tutorials/beginner/nlp/sequence_models_tutorial.html
3. Format the data in correct way - to put into ^ model and see if we get some results 


<!-- Things that need to be understood from sailing coach:
1. How will the results be used? Are false positives worse than false negatvies etc?
2. We need more balanced data

Technical Questions:
1. DataCleaning 
    1. Best way to standardize each file.
        * Standardize Longitude and Latitude (Unsure if subtract mean and standard deviation is the best way).
        * Sog - speed (unsure what the best way to standardize)
        * Cog any chance we can get angle from wind?
        * Other features should be removed.

Understand what the estimator is predicting as in what categories it is bad at predicting.  -->


Questions
* is the frequency all the same of the data? points per secob d