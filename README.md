# Titanic-Submission---Machine-learning

Using machine learning to create a model that predicts which passengers survived the Titanic shipwreck.
 
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this project, I will complete the analysis of what sorts of people were likely to survive. In particular, I will apply the tools of machine learning to predict which passengers survived the tragedy.

A good first step is to think logically about the columns and what we're trying to predict. What variables might logically affect the outcome of survived? (reading more about the Titanic might help here).

We know that women and children were more likely to survive. Thus, Age and Sex are probably good predictors. It's also logical to think that passenger class might affect the outcome, as first class cabins were closer to the deck of the ship. Fare is tied to passenger class, and will probably be highly correlated with it, but might add some additional information. Number of siblings and parents/children will probably be correlated with survival one way or the other, as either there are more people to help you, or more people to think about and try to save.

There's a less clear link between survival and columns like Embarked (maybe there is some information about how close to the top of the ship people's cabins were here), Ticket, and Name.

This step is generally known as acquiring domain knowledge, and it fairly important to most machine learning tasks. We're looking to engineer the features so that we maximize the information we have about what we're trying to predict.

I'll be using python 3, the pandas library, and scikit-learn to analyze our data and create a submission.
