# Statistical Modeling for Titanic Disaster
### Overview:
- The Titanic: Machine Learning from Disaster competition on Kaggle is a beginner level Modeling competition. There are many controversies revolving around the survivors of the disaster. My quest was to determine the factors that contributed to the survival rates of people. There are a number of attributes which was thoroughly studied. I had the opportunity to try out advanced Feature Engineering and complex ensemble models during this competition.
- I am extremely thankful to the Kaggle community and have referred tons of kernels before writing mine. 
#### Task: 
- We need to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).
#### Attributes Table:
| **Variable** | **Definition**                             | **Key**                                        |
|--------------|--------------------------------------------|------------------------------------------------|
| survival     | Survival                                   | 0 = No, 1 = Yes                                |
| pclass       | Ticket class                               | 1 = 1st, 2 = 2nd, 3 = 3rd                      |
| sex          | Sex                                        |                                                |
| Age          | Age in years                               |                                                |
| sibsp        | # of siblings / spouses aboard the Titanic |                                                |
| parch        | # of parents / children aboard the Titanic |                                                |
| ticket       | Ticket number                              |                                                |
| fare         | Passenger fare                             |                                                |
| cabin        | Cabin number                               |                                                |
| embarked     | Port of Embarkation                        | C = Cherbourg, Q = Queenstown, S = Southampton |

#### Variable Notes
**pclass:** A proxy for socio-economic status (SES)
- 1st = Upper
- 2nd = Middle
- 3rd = Lower

**age:** Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

**sibsp:** The dataset defines family relations in this way...
- Sibling = brother, sister, stepbrother, stepsister
- Spouse = husband, wife (mistresses and fiancés were ignored)

**parch:** The dataset defines family relations in this way...
- Parent = mother, father
- Child = daughter, son, stepdaughter, stepson
- Some children travelled only with a nanny, therefore parch=0 for them.
