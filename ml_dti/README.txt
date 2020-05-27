Data analysis of covid19 protein interaction with drug and herbal compound 

data = initial data
data2 = data for code, first attempt
data3 = data for code2, model with 'balanced' setting
data4 = data for code3, positive data oversampled with SMOTE
data5 = data for code5, dti with spike interaction oversampled with SMOTE

to prepare the data start from data(n) folder, combine-> label -> bagidata
to start the machine learning algorithm in code(n), cara1 for RF, MLP_SVM for MLP and SVM
model will be saved in data(n)/model and result will be saved in data(n)/hasil_pred

to merge the prediction result from ones with SMOTE, run data(n)/hasil_pred/mergesmote

to see the plot distribution, check data3 folder or run the Plot3d in code3
