# deep-learning-challenge - This is module 21 for Columbia's Data Analytics Bootcamp. 
Overview:

 

use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

 

Data Processing

Target Variables:

APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
 

Model Features:

IS_SUCCESSFUL—Was the money used effectively
 

Should be removed:

EIN and NAME—Identification columns
Compiling, training, and evaluating the model:

The data had three layers and an output layer. All the activations functions were “relu” besides the third layer which was sigmoid. The first layer had 80 units, whereas the 2nd had 30, and the third had 20.

I was not able to reach the target model performance after taking many steps attempting changes. Between different activation methods on layers, more layers, as well as less layers. I feel like this subject was the least explained to us in class in terms of the science behind these factors. It felt like randomly making changes without having the deep understanding of what consequences the output will show due to this.
