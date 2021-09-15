# Bandgap energy prediction in material science.

This package provides a machine learning model trained based on experimetally measurements to predict the bandgap energy (Eg) for  materials through Lines of python codes.


The package used while writing the code are-:

pymatgen
scikit-learn
pandas
NumPy

#How to use the following code-:

You should create a .xlsx file named to_predict.xlsx, in which the compositions  are listed in the first column with the header "Composition".


After doing with the_predict.xlsx, you can get the Eg prediction by:

#mainmodel.py

mainmodel.py will automatically read materials.xlsx and TrainingSet.xlsx to generate a prediction. 
A classifier will first categorize a composition into metals (Eg = 0) or nonmetals (Eg > 0), then the Eg of nonmetals will be predicted with a regressor. 
After running, you will get a .xlsx file named predicted.xlsx in the same directory, in which the predicted Eg is provided next to the composition so predicted.






# band-gap-prediction-using-machine-learning-model.
