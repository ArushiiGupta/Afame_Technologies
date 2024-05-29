# Afame_Technologies 
# Titanic Survival Predicton
The sinking of the Titanic is one of the most infamous shipwrecks in history.
On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank
after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone on board,
resulting in the death of 1502 out of 2224 passengers and crew.
![website-feature---national-titanic-remembrance-day---april-15](https://github.com/ArushiiGupta/Afame_Technologies/assets/93914809/c43a7a10-5aec-4023-94dd-0ceca494bda3)

# Problem Statement
We are developing a machine learning model to understand the relationship between passenger characteristics and their survival outcomes, and then use this model to predict the survival chances of passengers whose data the model has not previously encountered.

This task is a binary classification problem in machine learning because we are categorizing the outcomes of passengers as either having survived or not survived the Titanic disaster.

# Dataset
Below are the description of the features in the data:

Survival: 0 = Did not survive, 1 = Survived

Pclass: Ticket class where 1 = First class, 2 = Second class, 3 = Third class. This can also be seen as a proxy for socio-economic status.

Name: Name of the Passanger abaord the titanic

Sex: Male or female

Age: Age in years, fractional if less than 1

SibSp: Number of siblings or spouses aboard the titanic

Parch: Number of parents or children aboard the titanic

Ticket: Passenger ticket number

Fare: Passenger fare

Cabin: Cabin number

Embarked: Point of embarkation where C = Cherbourg, Q = Queenstown, S = Southampton

# Evaluation Metrics
The evaluation metric of this competition is the percentage of passenger data in the test set that are correctly predicted by our model. This is known as accuracy.
