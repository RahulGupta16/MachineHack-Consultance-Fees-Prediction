# MachineHack-Consultance-Fees-Prediction
We have all been in situation where we go to a doctor in emergency and find that the consultation fees are too high. As a data scientist we all should do better. What if you have data that records important details about a doctor and you get to build a model to predict the doctor’s consulting fee.? This is the hackathon that lets you do that.


Size of training set: 5961 records
Size of test set: 1987 records
FEATURES:
Qualification: Qualification and degrees held by the doctor
Experience: Experience of the doctor in number of years
Rating: Rating given by patients
Profile: Type of the doctor
Miscellaeous_Info: Extra information about the doctor
Fees: Fees charged by the doctor
Place: Area and the city where the doctor is located.

## Evaluation
Metric
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the predicted value and observed score values. The final score calculation is done in the following way:
Submissions are evaluated on Root-Mean-Squared-Log-Error (RMSLE) error = RMSLE (error)
Score = 1 – error

## Final_Train.xlsx
Contains the labelled texts with the Degrees, City, Locations and various other attributes.
## Final_Test.xlsx
test.csv contains texts with some attributes for which the participants are expected to predict the consultance fees.
## Sample_submission.csv
Sample_submission.csv contains the submission format for the prediction of the consultance fees in xlsx extension.

## Public Score : 0.71165330
## Local Score :  0.7234457451248648
