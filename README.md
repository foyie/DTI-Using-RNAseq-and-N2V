# Drug-Target-Identification-Using-Biological-Information-and-Node2vec

## Identification of Human Drug Targets for COVID-19 Based on Subcellular Localization Information, Gene Expression Data and Node2vec

For the last few years, humans have been searching for a good solution to 
the lethal disease of COVID-19. Finding human proteins that can be drugged to fight 
diseases like this is vital. Identification of essential proteins is an integral part of 
human drug design. Wet lab studies like single gene knockouts, RNA interference, 
and anti-sense RNA are employed to discover essential proteins. Despite being exceedingly accurate, these methods are costly and time-consuming. So, this led to an
increase in the demand for computational methods. The two main categories for this 
strategy are topological approaches and sequence based techniques. While sequence
based approaches use the sequence features for the predicting essential proteins, the 
topology focused methods use the topological aspects of the PPI Networks. Simply 
using topological features to predict essential proteins produces less accurate predictions. Hence, this research proposes a machine learning-based methodology for 
identifying COVID-19 drug targets by integrating several biological information. 
RNA-Sequence and subcellular location data are used as the features. This forms the 
weighted PPI network using Pearson Correlation coefficient after performing Principal Component Analysis. The topological features for the proteins are obtained 
from the feature vector set using node2vec. Lastly, the best features are selected,
which will be used as input for the machine learning (ML) models. ML models like 
Naïve Bayes Classifier, Logistic Regression, Random Forest, AdaBoost, Support 
Vector Classification and XGBBoost Classifier are trained on the data. The novel 
drug targets for COVID-19 are then identified by implementing the models which 
show the best performance. 

### The workflow of the project: 

![Slide2](https://github.com/foyie/Drug-Target-Identification-Using-Biological-Information-and-Node2vec/assets/89987028/ec4adc03-ef43-4e0a-a63e-f8115013c047)
