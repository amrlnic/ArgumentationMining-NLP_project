- ArgumentMiningDataframeCreation.ipynb
	- Notebook for creating the pickle file containing the processed pandas dataframe
	- It is necessary to have the zip containing the raw dataset "Dataset[1480].zip" in the same folder as the notebook

- Argumentation_prem_conc_classification.ipynb
	- Notebook for the recognition of premise / conclusion sentences
	- It is necessary to have the pickle file containing the processed dataset "dataset.pkl" in the same folder as the notebook

- Argumentation_type_classification.ipynb
	- Notebook for the recognition of different types of argumentative sentences
	- It is necessary to have the pickle file containing the processed dataset "dataset.pkl" in the same folder as the notebook

- multilabelArgumentation_type_classification.ipynb
	- Notebook for the recognition of different types of argumentative sentences with a multilabel model
	- It is necessary to have the pickle file containing the processed dataset "dataset.pkl" in the same folder as the notebook

- argumentation_prem_conc_classification_reults.txt
	- In this file are the results of the tests on the task of classification of premise / conclusion sentences
	- Remember to have it in the same folder as the Argumentation_prem_conc_classification.ipynb notebook to append the results of new experiments

- argumentation_type_classification_results.txt
	- In this file are the results of the tests on the task for the identification of argumentative sentence types
	- Remember to have it in the same folder as the Argumentation_type_classification.ipynb notebook to append the results of new experiments