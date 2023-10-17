ReadMe of findings:

From this work on the classification of whether individuals would respond positively to
telemarketting campaings.
 4 models were compared for their ability to minimize false negative values while still maintaining 
the ability to at correctly categorize at minimum %50 of true negative values. 
The CRISP DM approach was utilized in solving this problem by first following all steps and then itteratively
making changes as required. This included applying further preprocessing of data by means of logistic scaling,
dropping "unknown" values, abandoning all encoders except One_hot encoder for this excercise and 
further modifying the models search parameters for optimization.

The final result yielded that the SVM model was most capable of meeting the needs stated for optimizing true
positive outcomes. Although this model did not have the best area under the curve for the ROC, it was 
best for determining whether a person could be a potential customer. 

Some issues however found in the data was the duration of the phone calls. This feature did have a positive impact
on the outcome however noone can buy anything if the phone call is too short. Therefore it may be necessary to 
further deterine which individuals were more prone to prolonged phone calls as this seems to be a casue and 
effect issue. For this purpose however of creating the best model it was still included, though for practical
application i dont know that it would be a useful pre-screening feature since this can only be collected after the 
successful or unseccesful phone call.

 Furthe findings of the modelling effort can be summarized as follows in as non-technical terms as possible:
1. The duration of the phone call is the largest indicator of success, this means that further analysis may
 be required in order to determine which individual stay on the phone longer.
2. with regards to months, most months do not have a large impact on the outcome, 
however it is noticeable that the month of august had a positive impact, while the month of july
 had a largely negative impact. This behaviour could be driven by social factors such as vacation times, 
or other factors such as the end of tax season in portugal and when people recieve their tax returns.
3. With regareds to education level, people with higher education levels had larger chance of a positive 
outcome. People with only 6 years of education being negatively influenced to creating a nother bank
 account, followed closely by those with only a high school level of education. 
Potentially explaining in simpler terms to these individuals how they would benefit from the new 
accounts would be useful if correctly applied.
4. Married individuals showed the highest chance of positive outcome of all marital statuses while 
single people were negatively inclined to getting a new bank account.
5. job type had minimal impact on whether people wanted to get loans or not.
6. People with loans are negatively prone to creating a new bank account, potentially due to lack of 
liquid funds.
7. People who had been previously contacted were negatively inclined to getting another bank account.
 This being the single largest negative factor in this model.
8. The number of times the telemarketter reached out to an individual had a slight negative effect on outcome, this would mean that the telemarketters should aim to make a sale on the first time reaching out to a potential customer.