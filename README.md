
# Motivation
write some blurb about why you are doing your project. What you interested in. 

# Outline
* [Learning Stuff Section](#Learning-Stuff)

# Notebook
* Needs to be clean and organized
    * markdowns
    * introduction
        * outline
            * table of contents if possible
    * clear comments
    
    
* In order you should have
    * introduction
    * obtain section
    * scrubbing
        * handling null values
        * handling placeholders
        * handling outliers
        * etc
    * eda section
        * questions clearly stated
            * question
            * investigation + eda
            * conclusions + insights + recommendation
        * eda summary
    * modeling
        * model
        * iterate by using those results to make a new model
        * repeat 
        * final model - **do not have multicollinearity**
            * **DON'T**
                * have multicollinearity
                * pvalues > 0.05
                * P(F) > 0.05
            * your price equation written out 
                * $price = 23\text{sqft_living} + \dots$
                * writing a latex equation
                
                $$p = \beta_1 f_1 + \beta_2 f_2 + \dots$$
                
                $$p = 1232 sqftliving + 3232 grade + \dots$$
                
            * final model sm.OLS.summary()
            * model validation
                * train test split
                * cross validation in sklearn using
                * show the scores and interpret them
    * recommendations
    * conclusion
    * further work



# Slideshow
* 6-8/10 slides
* not too text heavy
* good visual aids
* model summary for features
    * insights
* recommendations
* further investigation
* thank you slide



# README.md
Either
    * convert notebook
or
    * intro
    * outline
    * notebooks used
    * conclusion
        * final model equation



# Video
* present your project
* upload to youtube, google drive or other cloud service



# Blog
* 800 words
* add some visuals
* have fun with it

# Learning Stuff
Here we will learn things about other things

[Back to Outline](#Outline)
