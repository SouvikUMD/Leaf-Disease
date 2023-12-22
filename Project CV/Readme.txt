STEPS TO REPRODUCE THE LEAF DISEASE CLASSIFIER WEB PAGE

1) Go to your Kaggle account and get the api token. (It will be downloaded as kaggle.json)
2) Run LeafDisease_Arnav.ipynb:
	a) Drop the kaggle.json file.
	b) run each cell to train and test the models.
	c) download the saved models. 
	[ You can just train and download the MobileNetV2 since it had the best results ]
3) create ngrock account and get tour authentication token.
4) Run Classifier_webpage.ipynb:
	a) Upload your downloaded model.
	b) Run each cell.
	c) A local server link will appear in the output.
	d) Click on it and the classifier web page will open.